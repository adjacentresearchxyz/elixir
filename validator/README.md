# Running a Validator 

Full Documentation [here](https://docs.elixir.finance/running-an-elixir-validator)

```
# edit the `env` vars in the `Dockerfile`
docker build . -f Dockerfile -t elixir-validator
docker run -d --restart unless-stopped -p 17684:17684 -p 17690:17690 --name elixir-validator elixir-validator
```
