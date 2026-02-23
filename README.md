# Models Used by PlentySound for Word Detector


### Deployment

NOTE: There is a workflow to dispatch compressed models available as project artifacts.

* **Add new model**:

_If you need to add a new model, just upload into a folder on root project dir and place the folder name on [.github/workflows/package-models.yml](.github/workflows/package-models.yml)_
```bash
env:
    MODELS: >-
      vosk-model-small-pt-0.3
      new-model-lang-0.0.0 # <<< here
```

### Download Artifacts

After running the **Package Models** workflow, the compressed model archives are available for download on the [Actions artifacts page](https://github.com/yuri-potatoq/plentysound-vosk-models/actions).
