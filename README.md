# concourse-conondrum

This repo is a test to determine whether many resources listed in a `passed` attribute at the `get` steps of a job act as a logical `AND` or `OR` operator.

## Usage

Deploy on your local instance of Concourse with :

```shell
$ fly -t local sp -p derp -c pipeline.yml -l secrets.yml
```

This was tested under Concourse `3.1.1`.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
