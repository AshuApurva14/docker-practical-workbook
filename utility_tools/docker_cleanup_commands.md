## Docker Clean up Commands

---


```bash
docker container rm -f $(docker container ls -aq)

```


---

```bash
docker image rm -f $(docker image ls -f reference='diamol/**' -q)

```
