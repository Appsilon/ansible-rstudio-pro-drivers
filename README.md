# ansible-rstudio-pro-drivers

Install Posit/RStudio Professional Drivers

## Table of content

- [Default Variables](#default-variables)
  - [rstudio_pro_drivers_dependencies](#rstudio_pro_drivers_dependencies)
  - [rstudio_pro_drivers_version](#rstudio_pro_drivers_version)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### rstudio_pro_drivers_dependencies

System dependecies required for using Drivers on Debian/Ubuntu ([Posit/RStudio docs](https://docs.posit.co/pro-drivers/workbench-connect/#step-1-install-dependencies))

#### Default value

```YAML
rstudio_pro_drivers_dependencies: [unixodbc, unixodbc-dev]
```

### rstudio_pro_drivers_version

Version of Posit/RStudio Professional Drivers.

Release notes: <https://docs.posit.co/pro-drivers/documentation/>

#### Default value

```YAML
rstudio_pro_drivers_version: 2023.12.1
```



## Dependencies

None.

## License

MIT

## Author

appsilon
