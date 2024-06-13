# BDP2 mid term review
```
docker run -d --rm --name my_jupyter -v ~/mid-term_review/work:/home/jovyan -p 80:8888 --network bdp2-net -e JUPYTER_ENABLE_LAB=yes -e JUPYTER_TOKEN="bdp2_password" --user root -e CHOWN_HOME=yes -e CHOWN_HOME_OPTS="-R" mid-term
```
