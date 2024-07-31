This is an example of how to use Hierarchy Controller (aka HNC) with Config Sync
unstructured repos. It's used in the HNC e2e tests.

You might ask: if this is really an unstructured repo, why does it look so...
structured? Good question, smart engineer! It's because this was created by
taking a structured repo and running it through the [ans2hns (abstract to
hierarchical) KPT
function](https://github.com/kubernetes-sigs/multi-tenancy/tree/master/incubator/hnc/tools/ans2hns).
Specifically, this is the output of the `simple-1` example repo from that
external repo, _after_ it's been run through the kpt fn.
