docker exec 045deb1c6b38 -it 
superset superset fab create-admin
docker exec 045deb1c6b38 
              --username admin
              --firstname Superset
              --lastname Admin
              --email admin@superset.com
              --password admin
          
docker exec -it 045deb1c6b38 bash
superset superset fab create-admin \
              --username admin \
              --firstname Superset \
              --lastname Admin \
              --email admin@superset.com \
              --password admin
