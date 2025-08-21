# 3Dclusters

A tiny framework-free web app that visualizes the k-means clustering algorithm on a rotatable 3D scatter plot.

Files:
- `index.html` — single-file front-end. Open in a browser (see below).

Run locally:

1. From the project root start a simple static server. Example using Python 3:

```bash
python3 -m http.server 8000
```

2. Open http://localhost:8000/index.html in your browser.

Controls:
- Drag the canvas to rotate the view.
- Mouse wheel to zoom.
- Choose k (2–6), click "Init centroids" to create k colored centroids.
- Click "Assign points → closest centroid" to connect each point to its nearest centroid.
- Click "Move centroids to centroids (update)" to move centroids to cluster means.
- Repeat assign/update to perform k-means iterations. Click "Restart" to sample a new dataset.

This app intentionally uses no frameworks so it's easy to read and modify.