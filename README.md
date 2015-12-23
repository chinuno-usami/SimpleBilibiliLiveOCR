## SimpleBilibiliLiveOCR
A simple OCR in order to recognise the Captcha of bilibili live
## Dependencies
PIL or Pillow
## Usage

``` bash
python biliocr.py <image_file>
```

or import as a module

```python
import biliocr
result = biliocr.procimg("image.jpg")
if result:
    print result
else
    print "failed"
```
