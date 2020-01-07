# override-chain

## usage

```typescript
import OverrideChain from 'override-chain'

function pushStateOverride() {
    console.log(arguments)
}

MethodChain.add(history, 'pushState', pushStateOverride)
```
