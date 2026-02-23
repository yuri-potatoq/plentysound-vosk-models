# Models Used by PlentySound for Word Detector


### Deployment

NOTE: There is a workflow to package and publish compressed models as GitHub releases.

* **Add new model**:

_If you need to add a new model, just upload into a folder on root project dir and place the folder name on [.github/workflows/package-models.yml](.github/workflows/package-models.yml)._
```bash
env:
    MODELS: >-
      vosk-model-small-pt-0.3
      new-model-lang-0.0.0 # <<< here
```

_Then after that you can commit and push and finally go to [Package Models Worflow](https://github.com/yuri-potatoq/plentysound-vosk-models/actions/workflows/package-models.yml) and trigger it._

### Download Models

After running the **Package Models** workflow, the compressed model archives are available for direct download on the [latest release](https://github.com/yuri-potatoq/plentysound-vosk-models/releases/latest).
