# Cadmus Itinera API

This is the second iteration of Itinera and will replace the [old repository](https://github.com/vedph/cadmus_itinera_api).

🐋 Quick Docker image build (you need to have a `buildx` container):

```bash
docker buildx create --use

docker buildx build . --platform linux/amd64,linux/arm64,windows/amd64,windows/arm64 -t vedph2020/cadmus-itinera-api:10.0.0 -t vedph2020/cadmus-itinera-api:latest --push
```

(replace with the current version).

>Note: when developing, if you need to use bibliography API just run it from `CadmusBiblioApi\CadmusBiblioApi` with command `dotnet run`.
