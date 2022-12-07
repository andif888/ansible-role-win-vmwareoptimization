# ansible-role-win-vmwareoptimization

Ansible Role to run VMwareOSOptimizationTool

## Table of content

- [Default Variables](#default-variables)
  - [ps_tools_commandline_args](#ps_tools_commandline_args)
  - [ps_tools_download_url](#ps_tools_download_url)
  - [ps_tools_filename_zip](#ps_tools_filename_zip)
  - [vmware_optimization_tool_commandline_args](#vmware_optimization_tool_commandline_args)
  - [vmware_optimization_tool_download_url](#vmware_optimization_tool_download_url)
  - [vmware_optimization_tool_filename_exe](#vmware_optimization_tool_filename_exe)
  - [vmware_optimization_tool_install_path](#vmware_optimization_tool_install_path)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Default Variables

### ps_tools_commandline_args

#### Default value

```YAML
ps_tools_commandline_args: -i 1 -s
```

### ps_tools_download_url

#### Default value

```YAML
ps_tools_download_url: https://download.sysinternals.com/files/PSTools.zip
```

### ps_tools_filename_zip

#### Default value

```YAML
ps_tools_filename_zip: PSTools.zip
```

### vmware_optimization_tool_commandline_args

#### Default value

```YAML
vmware_optimization_tool_commandline_args: -v -o -SyncHkcuToHku Enable -VisualEffect
  Balanced -Notification Disable -WindowsUpdate disable -OfficeUpdate Enable -WindowsSearch
  SearchboxAsIcon -StoreApp remove-all -Background "#0063B1" -Firewall Enable -AntiVirus
  Enable -SecurityCenter Enable -SmartScreen Disable
```

### vmware_optimization_tool_download_url

#### Default value

```YAML
vmware_optimization_tool_download_url: https://download3.vmware.com/software/vmw-tools/osoptimization/VMwareHorizonOSOptimizationTool-x86_64-2107.exe
```

### vmware_optimization_tool_filename_exe

#### Default value

```YAML
vmware_optimization_tool_filename_exe: VMwareHorizonOSOptimizationTool.exe
```

### vmware_optimization_tool_install_path

#### Default value

```YAML
vmware_optimization_tool_install_path: C:\Windows\Temp
```



## Dependencies

None.

## License

license (GPL-2.0-or-later, MIT, etc)

## Author

andif888
