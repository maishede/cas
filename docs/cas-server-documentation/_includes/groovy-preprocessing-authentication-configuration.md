{% include casproperties.html properties="cas.authn.core.engine.groovy-pre-processor" %}

The script itself may be designed as:

```groovy
def run(Object[] args) {
    def transaction = args[0]
    def logger = args[1]
    true
}

def supports(Object[] args) {
    def credential = args[0]
    def logger = args[1]
    true
}
```
