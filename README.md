# Dashing-icinga2

## Run
```docker run -d -p 3030:3030 evanhoucke/dashing-icinga2```

And point your browser to [http://localhost:3030/](http://localhost:3030/).


## Configuration
### Dashboards
To provide a custom dashboard, use container volume **/dashboards**:

```docker run -v=/my/custom/dashboards:/dashboards -d -p 3030:3030 evanhoucke/dashing-icinga2```

### Jobs
To provide custom jobs, use container volume **/jobs**:

```docker run -v=/my/custom/job:/jobs -d -p 3030:3030 evanhoucke/dashing-icinga2```

### Widgets

Also you can use local custom widgets

```docker run -v=/my/custom/widgets:/widgets -d -p 3030:3030 evanhoucke/dashing-icinga2```

