# OpenROAD callgrind report

The repository provides a report with call graphs for the design build steps in the OpenROAD project.
The call graphs are generated with [callgrind](https://valgrind.org/docs/manual/cl-manual.html) and visualized with [speedscope](https://github.com/jlfwong/speedscope).

To read the report locally, run `python -m http.server` command in the [docs](docs/) directory, e.g.:

```
cd docs
python -m http.server 8080
```

makes it available over http://localhost:8080
