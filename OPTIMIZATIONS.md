# Performance Optimizations

## 2025-02-26 - Image Optimization

**Optimization:** Lossless compression of large images (>100KB) in `images/` using `sharp`.
**Rationale:** Reduce repository size and faster download/load times.
**Impact:** ~2MB total size reduction (~66% reduction for targeted files).

### Details

The following images were optimized:

| File | Original Size | Optimized Size | Reduction |
|---|---|---|---|
| images/cover.jpg | 302KB | 175KB | ~42% |
| images/figure01.png | 109KB | 37KB | ~66% |
| images/figure02.png | 131KB | 42KB | ~68% |
| images/figure03.png | 120KB | 38KB | ~68% |
| images/figure04.png | 187KB | 67KB | ~64% |
| images/figure05.png | 142KB | 39KB | ~72% |
| images/figure07.png | 107KB | 30KB | ~72% |
| images/figure16.png | 104KB | 30KB | ~71% |
| images/figure20.png | 194KB | 71KB | ~63% |
| images/figure30.png | 178KB | 48KB | ~73% |
| images/figure31.png | 193KB | 53KB | ~72% |
| images/figure39.png | 106KB | 28KB | ~73% |
| images/figure43.png | 123KB | 32KB | ~74% |
| images/figure44.png | 165KB | 42KB | ~74% |
| images/figure45.png | 101KB | 27KB | ~73% |
| images/figure46.png | 184KB | 49KB | ~73% |
| images/figure47.png | 105KB | 25KB | ~76% |
| images/figure51.png | 111KB | 28KB | ~75% |
| images/figure53.png | 127KB | 50KB | ~60% |
| images/figure54.png | 122KB | 37KB | ~70% |
| images/figure56.png | 119KB | 34KB | ~71% |

**Total Saved:** ~2MB
