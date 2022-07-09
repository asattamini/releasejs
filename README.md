# ReleaseJS

## Configuration

### Install releasejs locally as a dev dependency or globally. Usually, when working on multiple projets, having releasejs globally is preferred as it can be invoked by npx.

```
npm install -g releasejs
```

```
 "devDependencies": {
    "releasejs": "^1.0.0"
  }
```

### Run the commando to make a release

```
npx releasejs {type}
```

Options for type argument: patch, minor or major.

Be sure to be on "develop" branch.
