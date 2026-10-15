# Awesome-Webgl-3D-Web-Engines

### Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Webgl-3D-Web-Engines

## Top WebGL & 3D Web Engines Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Browser 3D Graphics, WebGL/WebGPU Engines, Interactive Scenes, Geospatial Visualization & Real-Time Rendering on the Web*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **WebGL & 3D Web Engines**. These tools render interactive 3D content in the browser—product configurators, games, digital twins, maps, and immersive experiences—without plugins.



**Examples** include PlayCanvas, Three.js, Babylon.js, A-Frame, CesiumJS, Verge3D, Spline Cloud, Sketchfab, Unity WebGL, Model-Viewer, and **Babylon.js** (`BabylonJS/Babylon.js`)—powerful, beautiful, simple, and open 3D on the web.



**Open-source emphasis**: The browser 3D stack is overwhelmingly open source. **Three.js**, **Babylon.js**, **PlayCanvas**, **A-Frame**, **CesiumJS**, and **model-viewer** define the ecosystem. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Spline Cloud, Sketchfab, Verge3D-oriented hosting](https://spline.design/)**  

  Design-to-web 3D platforms and marketplaces for publishing interactive scenes and models with minimal engineering.



- **[Unity WebGL builds & cloud content pipelines](https://unity.com/)**  

  Export Unity projects to WebGL for browser deployment; often paired with cloud hosting and asset pipelines.



- **[PlayCanvas (hosted editor / enterprise)](https://playcanvas.com/)**  

  Cloud-hosted 3D editor and publishing workflow built on the open PlayCanvas engine.



- **[Other commercial 3D web platforms](https://sketchfab.com/)**  

  Additional model hosting, configurator SaaS, and WebGL application services.



## Open-Source GitHub Projects



### Core Engines & Frameworks



- **[Three.js](https://github.com/mrdoob/three.js)**  

  The most widely used open WebGL library—scenes, materials, cameras, loaders, and a vast examples ecosystem for any 3D web project.



- **[Babylon.js](https://github.com/BabylonJS/Babylon.js)**  

  Powerful open WebGL/WebGPU engine—physically based rendering, tools, inspectors, and first-class TypeScript support for games and visualization.



- **[PlayCanvas Engine](https://github.com/playcanvas/engine)**  

  Open-source WebGL game engine with entity-component architecture; powers the PlayCanvas editor and many production apps.



- **[A-Frame](https://github.com/aframevr/aframe)**  

  Open HTML-based framework for WebXR and 3D scenes—built on Three.js, ideal for VR/AR and declarative content.



- **[CesiumJS](https://github.com/CesiumGS/cesium)**  

  Open geospatial 3D globe and map engine—streaming terrain, imagery, and 3D Tiles for digital earth applications.



- **[model-viewer](https://github.com/google/model-viewer)**  

  Open web component from Google for rendering glTF/GLB models with lighting, AR, and progressive enhancement.



### Specialized & Adjacent Open Projects



- **[OGL](https://github.com/oframe/ogl)**  

  Minimal WebGL library—smaller footprint alternative when Three.js is more than you need.



- **[ClayGL](https://github.com/pissang/claygl)**  

  Open WebGL graphic library focused on high-quality rendering and post-processing.



- **[vtk.js](https://github.com/Kitware/vtk-js)**  

  Open scientific visualization toolkit for the web—volumes, meshes, and data pipelines in the browser.



- **[Xeogl / other scene-graph engines](https://github.com/xeolabs/xeogl)**  

  Open engine options for architecture and engineering-style 3D viewing.



- **[glTF loaders & Khronos samples](https://github.com/KhronosGroup/glTF)**  

  Standard 3D transmission format and reference tooling used across all major engines.



- **[WebGPU exploratory engines & Three/Babylon WebGPU paths](https://github.com/gpuweb/gpuweb)**  

  Emerging open stacks targeting the next-generation web graphics API.



- **[React Three Fiber](https://github.com/pmndrs/react-three-fiber)**  

  Open React renderer for Three.js—declarative 3D in React applications.



- **[Threepipe / editor toolkits](https://github.com/search?q=three.js+editor+open+source)**  

  Community editors and pipelines built on Three.js for non-code scene authoring.



### Additional Strong Open-Source Options



- **General 3D web**: Three.js or Babylon.js.

- **Games / ECS**: PlayCanvas engine.

- **VR/AR-first**: A-Frame (+ Three.js).

- **Geospatial**: CesiumJS.

- **Product/model embed**: model-viewer.

- **React apps**: React Three Fiber.

- **Composable stacks**: glTF assets → Three/Babylon/PlayCanvas → optional physics → UI framework.

- Commercial tools still lead for designer-first editors, large model marketplaces, and turnkey Unity-to-web pipelines.



**Frameworks for building custom systems**:  

**Three.js** for maximum ecosystem and flexibility; **Babylon.js** for batteries-included rendering and tools; **PlayCanvas** for game-oriented ECS; **CesiumJS** for globe-scale data; **model-viewer** for simple product 3D.  

Pair with glTF as the asset interchange format.  

Fully open WebGL/3D web stacks are the default for serious browser 3D development.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- 3D web apps can be GPU- and bandwidth-intensive. Test on low-end devices, provide fallbacks, and respect user preferences (e.g. reduced motion). Be mindful of intellectual property when using third-party models.

- Open-source engines offer full control and no runtime license fees for the engine itself. Hosted design tools shift authoring UX to the vendor. Neither replaces performance budgets and accessible UX design.



---



**Made for creative technologists, graphics engineers, and teams shipping 3D on the web.**  

Let's expand open WebGL and WebGPU engines while recognizing the design workflows that commercial 3D web platforms deliver.
