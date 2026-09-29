# RunningHub-Custom-Nodes-Request
Request to add missing ComfyUI custom nodes to RunningHub, including Lonecat’s LC node suite and related dependencies.
# RunningHub Custom Nodes Request

This repository was created to organize a request for additional **ComfyUI custom node packages** to be reviewed and made available on **RunningHub**.

Several public ComfyUI workflows depend on these custom nodes, but they are currently unavailable in the RunningHub cloud environment.

Since RunningHub users cannot manually install missing custom nodes like they can in a local ComfyUI installation, this repository collects the required upstream repositories in one place to make the review process easier.

> **Important:** This repository does not redistribute, modify, or claim ownership of any of the custom nodes listed below. All code belongs to the respective original authors. The links below point directly to the original repositories.

---

## Lonecat Custom Node Suite

The following six repositories are maintained by **lonecatone23** and are used across multiple ComfyUI workflows.

### 1. ComfyUI_LC123_nodes

https://github.com/lonecatone23/ComfyUI_LC123_nodes

General-purpose LC custom nodes used for image processing, workflow utilities, prompting, pipelines and other advanced ComfyUI functions.

---

### 2. ComfyUI_LC_Vision_nodes

https://github.com/lonecatone23/ComfyUI_LC_Vision_nodes

Vision-related nodes used for image analysis, prompt enhancement and vision-based workflows.

Some missing nodes already encountered on RunningHub include:

- `LCVisionLoader`
- `LCVisionPromptEnhancer`

---

### 3. ComfyUI_LC_AV_nodes

https://github.com/lonecatone23/ComfyUI_LC_AV_nodes

Audio/video related custom nodes used by LC workflows.

---

### 4. ComfyUI_LC_AI_nodes

https://github.com/lonecatone23/ComfyUI_LC_AI_nodes

AI-related utilities and components used by Lonecat ComfyUI workflows.

---

### 5. ComfyUI_LC_ModelBuilder_nodes

https://github.com/lonecatone23/ComfyUI_LC_ModelBuilder_nodes

Custom nodes related to model building, model processing and advanced model operations.

---

### 6. ComfyUI_LC_MaskMaker_nodes

https://github.com/lonecatone23/ComfyUI_LC_MaskMaker_nodes

Custom nodes for creating and processing masks inside ComfyUI workflows.

---

## Additional Custom Node

### KreaSeedVarianceEnhancer

https://github.com/harukimix/KreaSeedVarianceEnhancer

This custom node is used by some **Krea 2** ComfyUI workflows.

Missing node encountered on RunningHub:

- `KreaSeedVarianceEnhancer`

---

# Request to the RunningHub Team

Hello RunningHub team,

Could you please review the custom node repositories listed above and, if they are compatible with RunningHub's environment and security requirements, consider making them available on RunningHub?

These repositories are dependencies of public ComfyUI workflows that currently load with missing or unknown nodes when imported into RunningHub.

The main request is for the complete **Lonecat LC custom node suite**:

- ComfyUI_LC123_nodes
- ComfyUI_LC_Vision_nodes
- ComfyUI_LC_AV_nodes
- ComfyUI_LC_AI_nodes
- ComfyUI_LC_ModelBuilder_nodes
- ComfyUI_LC_MaskMaker_nodes

Additionally, **KreaSeedVarianceEnhancer** is requested because it is required by some Krea 2 workflows.

Installing the complete packages instead of only individual nodes would improve compatibility with multiple public workflows that rely on different components from these repositories.

Thank you for taking the time to review this request.

---

## Original Authors

**Lonecat**

https://github.com/lonecatone23

**KreaSeedVarianceEnhancer — harukimix**

https://github.com/harukimix/KreaSeedVarianceEnhancer

Please refer to the original repositories for their latest source code, dependencies, installation instructions and licensing information.
