# DLC Site Configs
Exported, importable site configuration for the DLC

## Requirements
Requires export/import rake tasks in DLC v1.9.0+

## Structure
Subdirectories here are named by the slug of the site

## Importing
In this example, the **ldpd-dcv** repository is presumed to be checked out to `~/ldpd-dcv`, and this repository is assumed to be checked out to `~/dlc-site-configs`. In this example the slug of the site to be imported is `lehman`.

```bash
cd ~/ldpd-dcv
bundle exec rake dcv:sites:import directory=../dlc-site-configs/lehman
```

## Exporting
In this example, the **ldpd-dcv** repository is presumed to be checked out to `~/ldpd-dcv`, and this repository is assumed to be checked out to `~/dlc-site-configs`. In this example the slug of the site to be imported is `lehman`.

```bash
cd ~/ldpd-dcv
bundle exec rake dcv:sites:export slug=lehman directory=../dlc-site-configs/lehman
```



