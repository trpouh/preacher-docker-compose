# example sermon

This is an example sermon to showcase the `Sermon` psalm of the [preacher](https://github.com/trpouh/preacher).

## Usage

Just add it to your sermon like this:

```yaml
# sermon.yaml
psalms:
- type: Sermon
  id: remote-sermon
  sermon:
    repo: https://github.com/trpouh/preacher-example-sermon
    file: sermon.yaml
    branch: main
```