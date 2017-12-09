# kikibot

![hello](https://lh3.googleusercontent.com/TUO6zk_iRrW-YpQfW9Q4V6d_xLRQjlcjmtC1M-khKn1gxQZ6Zbo8QAo9-oyrq6Pc9LWtn1buiS9obKC19IDoY5ohBZvhWY2Qj8hVOv3UmnwLFCkqy7zz-8pOx6UkBQUUoTDbttPa6nPipDkJALkBkysqd47C8FQJkgAPcO-YFbEQWuuaXJ1k0nsgCIKItitx64sEuROfOrC3vvXoEM2vh-zmxMyVGtKYMUNnGz0XSa-C-6LG86jOAlqS0vQnZSU3luh5MrGZdMxHMcsCmBUKcjuOmxH7R9kvt6RRZ65bliVo0uHY1IBfVotGiILEwV9XJoU2TbPMPkKQx-9F6sWLinJZzj-0CTlalXT6TbS7Kcuy4pjlhy6HjASDvSYUwWtxOV-Cp6UGpHF7UHDLyW3JDEeXJ5YosOS-4vvKJlCLEQGkCsKmN09hf6c1dD21jm6h1uy3tu3VlKNHYY0UCReXwOR4jZvLY62BoRrQIrxoiD-dOsDoTb9BWBZzsBjGMr-Y4TaG2FkP5ZC60Qb3kKROE3yKUcfRXXM9qHB5vnXNrh5cNvN3WMSBAmLXa5E9chd-yddFZUvuxEH0siMNvbSffMrDFhY-VjHnia_qdyUAAcE=w886-h476-no)


## Use Azure app service editor

1. make code change in the online editor
2. open the console window and run

```
build.cmd
```

## Use Visual Studio 

### Build and debug
1. download source code zip and extract source in local folder
2. open {PROJ_NAME}.sln in Visual Studio
3. build and run the bot
4. download and run [botframework-emulator](https://emulator.botframework.com/)
5. connect the emulator to http://localhost:3987

### Publish back

In Visual Studio, right click on {PROJ_NAME} and select 'Publish'

For first time publish after downloading source code
1. In the publish profiles tab, click 'Import'
2. Browse to 'PostDeployScripts' and pick '{SITE_NAME}.publishSettings'


## Use continuous integration

If you have setup continuous integration, then your bot will automatically deployed when new changes are pushed to the source repository.



