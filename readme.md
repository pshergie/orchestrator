# 🔥 orchestrator 🔥
Orchestrator package to run split all cypress specs across n parallel docker containers based on a configuration file.

## ♟️ Orchestrator allow us to:

* Pares a config file 
* Execute n containers machines  in parallel
* Split all specs across all those machines 
* Collect all the execution results from those containers 
* Down all the running containers
* Generate one HTML report that has all specs execution results. 

## 👌 Installation:

```bash
npm -g install 0xislamtaha/orchestrator
```

## 🎮 Usage:

simple with a configuration file, execute the following commands
```bash
orchestrator --config ./src/config.json
```

If you need to overwrite any configuration, simplly path the new configuration as a prameter.
```bash
orchestrator --config ./src/config.json --parallelizm 2 --environment '{"DOCKER_TAG":"master_283"}' --browsers "[chrome, firefox]"
```

## 🎬 To-Do:

* Write full details readme.
* Export it to npm registry.
* Provide --help option.
* Demo it to the team.
