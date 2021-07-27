# cvat-cheat-sheet

## Where does cvat keep its dataset zip files?


For e.g. task 23, it's here:

```
/var/lib/docker/volumes/cvat_cvat_data/_data/tasks/23/export_cache
```

Note that this is owned by root, so use `sudo`:

```
sudo ls /var/lib/docker/volumes/cvat_cvat_data/_data/tasks/
```
