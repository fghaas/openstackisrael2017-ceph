## The unknown


### BlueStore

Note: Explain the original motivation behind BlueStore, why we want
it, what’s wrong with FileStore, and how BlueStore is implemented.


### Performance
with BlueStore

Note: Explain the implications that BlueStore has on throughput
(higher, since there are no more journal double-writes) and latency.


### Transition
to BlueStore

Note: Explain that starting with Luminous it’s quite easy to migrate
to BlueStore in a rolling fashion, taking out one OSD after another,
throwing its FileStore away, and then redeploying it with BlueStore.
