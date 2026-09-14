# MLOps 2026-27 Course Demos and Resources
This is a demo project for the Machine Learning Systems in Production (MLOps) 2025-26 course (Universitat Politècnica de Catalunya-BarcelonaTech (UPC), Spain).

This project follows the structure proposed by Lanubile et al. [1].

## Project milestones
<table>
    <thead>
        <tr>
            <th>Milestone</th>
            <th>Practice</th>
            <th>Tools</th>
            <th>Demo</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2"><b>Milestone 1 &mdash; Project Inception</b></td>
            <td>Selection of problem and requirements engineering for ML</td>
            <td>Model and dataset cards (by Hugging Face)</td>
            <td><a href="https://huggingface.co/docs/hub/model-card-annotated">Model card template</a>, <a href="https://github.com/huggingface/datasets/blob/main/templates/README_guide.md">Dataset card template</a></td>
        </tr>
        <tr>
            <td>Project coordination and communication</td>
            <td>Taiga, Trello, Slack</td>
            <td></td>
        </tr>
        <tr>
            <td rowspan="3"><b>Milestone 2 &mdash; Model building: repoducibility</b></td>
            <td>Project structure</td>
            <td>Cookiecutter data science template</td>
            <td><a href="docs/project-setup.md">Project setup guide</a></td>
        </tr>
        <tr>
            <td>Code and data versioning</td>
            <td>Git with GitHub Flow, DVC</td>
            <td><a href="docs/git-demo.md">Git demo</a>, <a href="docs/dvc-demo.md">DVC demo</a></td>
        </tr>
        <tr>
            <td>Experiment tracking</td>
            <td>MLflow</td>
            <td><a href="docs/mlflow-demo.md">MLflow demo</a></td>
        </tr>
        <tr>
            <td rowspan="4"><b>Milestone 3 &mdash; Model building: QA</b></td>
            <td>Energy efficiency awareness</td>
            <td>CodeCarbon</td>
            <td><a href="docs/codecarbon-demo.md">CodeCarbon demo</a></td>
        </tr>
        <tr>
            <td>Quality assurance for ML: static analysis</td>
            <td>Pynbilint (notebook + repository QA), Pylint, flake8</td>
            <td></td>
        </tr>
        <tr>
            <td>Quality assurance for ML: testing data and model</td>
            <td>Pytest, Great Expectations, Deepchecks (computer vision tasks)</td>
            <td>
                <a href="docs/pytest-demo.md">Pytest demo</a>,
                <a href="docs/great-expectations-demo.md">Great Expectations demo</a>,
                <a href="https://docs.deepchecks.com/stable/vision/auto_tutorials/quickstarts/plot_simple_classification_tutorial.html">Deepchecks demo</a>
            </td>
        </tr>
        <tr>
            <td>Quality assurance for ML: non-functional requirements</td>
            <td>SHAP, AIF360, TrustML</td>
            <td>
                <a href="https://shap.readthedocs.io/en/latest/text_examples.html">SHAP examples</a>
            </td>
        </tr>
        <tr>
            <td rowspan="2"><b>Milestone 4 &mdash; Model deployment: API</b></td>
            <td>ML system design</td>
            <td>Cloud platform selected by the students (VMs, Heroku, DigitalOcean, etc.)</td>
            <td><a href="docs/deployment/">Deployment guides</a></td>
        </tr>
        <tr>
            <td>APIs for ML</td>
            <td>FastAPI and Pytest (to test the API endpoints)</td>
            <td><a href="docs/fastapi-demo.md">FastAPI demo</a></td>
        </tr>
        <tr>
            <td rowspan="2"><b>Milestone 5 &mdash; Model Packaging</b></td>
            <td>Containers</td>
            <td>Docker, Docker Compose, Kubernetes</td>
            <td><a href="docs/docker-demo.md">Docker demo</a></td>
        </tr>
    </tbody>
</table>

## Additional tooling
Besides the tools mentioned in the milestones you can find more MLOps tools [here](https://agate-tangerine-725.notion.site/MLOps-tools-255624cb2156801e9a98db82fd911da2?pvs=74).
You might find some of them useful when developing your project.

## References
[1] F. Lanubile, S. Martínez-Fernández, and L. Quaranta, "Teaching MLOps in Higher Education through Project-Based Learning." SEET@ICSE 2023: 95-100. doi: [10.1109/ICSE-SEET58685.2023.00015](https://doi.org/10.1109/ICSE-SEET58685.2023.00015).

[2] F. Lanubile, S. Martínez-Fernández, and L. Quaranta, "Training future ML engineers: a project-based course on MLOps." IEEE Software 2024. doi: [10.1109/MS.2023.3310768](https://doi.org/10.1109/MS.2023.3310768).
