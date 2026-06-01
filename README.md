# set-pom-property-action
Surgically updates Maven `<property>` values in all `pom.xml` files using `sed`.

## Usage
```yaml
- uses: arvato-systems-jacs/set-pom-property-action@master
  with:
    properties: '{"a28.version":"9.1.5","commerce.version":"5.1.14"}'
```
