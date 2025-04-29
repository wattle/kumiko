

pkgx pipx install poetry

pkgx install poetry

pkgx poetry build


old shebang #!/usr/bin/env python3

# Setup 

pkgx python3 -m pip install opencv-python
pkgx python3 -m pip install requests

python3-opencv

pkgx poetry run python -m pip freeze > requirements.txt
https://realpython.com/dependency-management-python-poetry/#synchronize-your-environment


###  for deps
pkgx poetry self add poetry-plugin-export
pkgx poetry export --output requirements.txt
pkgx pip install -r

## Running 

mkdir panels
../../../kumiko/kumiko -i comic-page.png -s ./panels

mkdir -p tests/results/

for debug 
../../../kumiko/kumiko -i comic-page.png -s ./panels -d


Json output
[{"filename": "comic-page.png", "size": [3300, 5100], "numbering": "ltr", "gutters": [1, 34], "license": null, "panels": [[259, 511, 2758, 1246], [259, 1819, 2758, 1201], [259, 3054, 2758, 1529]], "processing_time": 1.2}]


clean up and use this 
https://maxhalford.github.io/blog/comic-book-panel-segmentation/
^ make that into a script

turn reader into lit elements?

json 

{
    file: ...
    size: ....
    panels: [
        {
           filename: ...,
           slug: ...
           boundarybox: []
        }
    ]


}

crazy segmentation https://github.com/antoinedelplace/comfyui_segment_anything-1