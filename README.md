# Usage 

### Please copy paste below code

```
module "testns" {
    source = "danpuz7/namespace/kubernetes"
    name   = "testns"
    annotations = {
        new = "application"
    }
    labels = {
        createdby = "danpuz7"
    }
}
```
