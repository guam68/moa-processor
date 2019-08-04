# moa-processor

## Goals

- [ ]  Take in an image of a shot grouping and a shot distance
    - Requirement: Item of known size captured in picture (quarter?)
- [ ] Find edges of all bullet holes
- [ ] Find center of bullet holes
- [ ] Find greatest distance between holes (px)
- [ ] Find edge of reference item
- [ ] Calculate diameter of reference item (px)
- [ ] Calculate distance between holes based on ref item (in)
- [ ] Calculate moa based on distance between holes and shot distance

### Stretch
- [ ] Batch processing
- [ ] Output a copy of the image with the moa labeled on the image


## Possible Hurdles
- Different colored targets
- Colors of target and holes similar enough to interfere with finding edges
- Tight grouping causing edges to blend


## Technologies
- Python
- NumPY?
- OpenCV?
- SciPy?
- Pillow?
