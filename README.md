
## 🛠️ Requirements and Installation
* Create the environment based out of environment.yaml
* Activate the environment
* Validated model : LanguageBind/Video-LLaVA-7B

```bash
git apply my_changes.patch
python -m videollava.serve.cli --model-path LanguageBind/Video-LLaVA-7B  --file <PATH_TO_VIDEO> --device cpu --mode ipex
```
