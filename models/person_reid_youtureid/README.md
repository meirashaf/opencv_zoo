# Youtu ReID Baseline

This model is provided by Tencent Youtu Lab [[Credits]](https://github.com/opencv/opencv/blob/394e640909d5d8edf9c1f578f8216d513373698c/samples/dnn/person_reid.py#L6-L11).

**Note**:
- Model source: https://github.com/ReID-Team/ReID_extra_testdata
- `person_reid_youtu_2021nov_int8bq.onnx` represents the block-quantized version in int8 precision and is generated using [block_quantize.py](../../tools/quantize/block_quantize.py) with `block_size=64`.

## Demo

Run the following command to try the demo:

```shell
python demo.py --query_dir /path/to/query --gallery_dir /path/to/gallery -v

# get help regarding various parameters
python demo.py --help
```

### License

All files in this directory are licensed under [Apache 2.0 License](./LICENSE).

## Reference:

- OpenCV DNN Sample: https://github.com/opencv/opencv/blob/4.x/samples/dnn/person_reid.py
- Model source: https://github.com/ReID-Team/ReID_extra_testdata
