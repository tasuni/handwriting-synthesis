# Handwriting Synthesis
<placeholder>

# Text image extraction from grid

box_extraction.py can be used to extract individual boxes from a grid, which may contain anything (handwritten font in our case).

To use the script, simply run
```python
python box_extraction.py extract <image_path> <extraction_folder>
```

An example for this would be
```python
python box_extraction.py extraction "images/hand_doc.jpg" "extracted/"
```
All the parameters required are strings.

Source for the box detection script : https://medium.com/coinmonks/a-box-detection-algorithm-for-any-image-containing-boxes-756c15d7ed26