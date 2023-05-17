# JSON Data Processor in LOLCode

## Running the code

```bash
run
```

Or in Docker:
```bash
docker run --rm -v $(pwd):/app/ -w /app --entrypoint "/app/run" python:3.10-slim
```

Or on Windows:
```bash
docker run --rm -v %cd%:/app/ -w /app --entrypoint "/app/run" python:3.10-slim
```

If you'd prefer Python code, you can run the above commands with `--python` 


## Sample output:

````
Patients
  Cheryl Adams
  Christina Adams
  George Adams
  Helen Adams
  Carl Alexander
...
  Patrick Wright

Nurses
[Ward 1]
  Nicole Campbell
  Roy Hunt
  Jesse Johnson
...
  Terry Ruiz
  Cheryl Stevens

Doctors
  Beverly Allen: 8-(368)867-0114
  Paul Andrews: 8-(537)325-2084
  Tammy Bailey: 7-(299)751-6590
...
````
