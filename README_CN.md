pip install onnx

pip install click

pip install magika


python /d/GitHub/magika/python/src/magika/cli/magika_client.py ./magika_client.py



macOS


```
python3 -m venv path/to/venv
source path/to/venv/bin/activate
python3 -m pip install xyz


pip install --upgrade pip
python3 -m pip install onnx
python3 -m pip install click
python3 -m pip install magika
```


cd python/src/magika/cli/
./magika_client.py ./magika_client.py



pip3 install magika


_extract_features_from_seekable
返回提取的内容 ModelFeatures

```
@dataclass(frozen=True)
class ModelFeatures:
    beg: List[int]
    mid: List[int]
    end: List[int]
    # for ISO
    offset_0x8000_0x8007: List[int]
    offset_0x8800_0x8807: List[int]
    offset_0x9000_0x9007: List[int]
    # for UDF
    offset_0x9800_0x9807: List[int]
```

