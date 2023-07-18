## WEB

```bash
$ npm install # or yarn install
```

```bash
$ npm run dev # or yarn dev
```

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## AI

```bash
$ brew install miniconda
# https://docs.conda.io/en/latest/miniconda.html
```

```bash
$ conda install flask pytorch torchvision
```
To install the required packages for machine learning and webhosting.

```bash
$ pip install Flask
```
Installs the Flask webserver tool.

```bash
$ python3 ai/server.py
```
Serves the project.

```bash
$ python3 ai/ml.py
```

Runs the pytorch example project.
The output should look like this:

```python
tensor([[0.3887, 0.1528, 0.4726],
        [0.7560, 0.7288, 0.7447],
        [0.7123, 0.7480, 0.4764],
        [0.3071, 0.0432, 0.7623],
        [0.4535, 0.0617, 0.7562]])
```