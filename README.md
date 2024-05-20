# Usage

### Please copy paste below code 
```
module "testns" {
  source = "farrukh90/namespace/kubernetes"
  name   = "testns"
  annotations = {
    new = "application"
  }
  labels = {
    createdby = "farrukh90"
  }
}

```
