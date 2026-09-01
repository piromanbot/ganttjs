# ganttjs

DHTMLX Gantt chart (edge CDN) with PDF/PNG export, based on the [export demo](https://docs.dhtmlx.com/gantt/demos/export-pdf-print/).

## Usage

Serve locally and open in a browser:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Use the buttons at the top to export to **PDF** or **PNG**, or **Print**.

Data is defined in `index.html` inside the `gantt.parse({...})` call — edit the `tasks` and `links` arrays as needed.
