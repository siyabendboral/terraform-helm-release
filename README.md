# Usage

### Please copy paste below code 
```
module "release" {
  source  = "siyabendboral/release/helm"
  name    = "testapplication"
  namespace = "testapp"
  values_yaml = <<EOF
EOF
}
```