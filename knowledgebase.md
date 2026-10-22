# Types of rollout strategy

### Recreate: 
- Destroy all the pods at once and create new pods at once. 
- This is not the default deployment strategy

### Rolling update
- Destroy one old pod and create one new pod.
- Repeating the same process untill all the old pods are removed.
- This is the default rollout strategy if nothing is specified.