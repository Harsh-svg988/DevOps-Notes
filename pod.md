# Notes

- pod
  - group of 1 or more containers
  - a group of some identical things which are independently alive (mental model)
  - they are co scheduled (means they come up together)
  - they are co located (same node)
  - a single pod can run multipls containers but generally single pod single container
  - It's like a single unit of executable docker compose (not exactly its more generic but yeah)
  - a pod can be thought of as a small machine inside our machine which can run multiple containers

  # Notes

- advntages of pod
  - If a container crashes -- automatically replaced

- advantages of replicaset (rs)
  - pod's or nodes crashes -- replaced (as long as capacity)
  - easy to scale in and out
  - create replicas

- commands
  - kubectl get rs