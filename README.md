# CodeIgniter Copy File 12
Copy file 12 is a sample module for CodeIgniter

|-- [CodeIgniter Composer Installer](https://github.com/kenjis/codeigniter-composer-installer).

|-- [Composer Installers Extender](https://github.com/oomphinc/composer-installers-extender)

## Install for CodeIgniter Composer Installer
at install.php after installation create an array item
```
'CiCopyFile' => array(
    'site'  => 'github',
    'user'  => 'andri-sudarmawijaya',
    'repos' => 'CiCopyFile',
    'name'  => 'CodeIgniter Copy File 12',
    'dir'   => array('controllers','models', 'views'),
    'msg'   => 'See https://github.com/andri-sudarmawijaya/CiCopyFile/',
    'example_branch' => 'master',
),
```

install script using this command
```
php bin/install.php CiCopyFile master
```

## Install for HMVC using Composer Installers Extender
```
composer require andri-sudarmawijaya/cicopyfile:1.0.x-dev
```

## Directory Structure
in CiCopyFile directory under vendor

```
andri-sudarmawijaya/
|   ├── controllers/
|   |   ├── CiCopyFile.php
|   ├── models/
|   |   ├── CiCopyFile_model.php
|   ├── views/
|   |   ├── CiCopyFile/
|   |   |   ├── CiCopyFile_list.php
|   |   |   ├── CiCopyFile-form.php
|   |   |   ├── CiCopyFile_read.php

```

## Directory Structure for CodeIgniter Composer Installer

under application directory will be :
```
├── controllers/
|   ├── CiCopyFile.php
├── models/
|   ├── CiCopyFile_model.php
|── views/
|   ├── CiCopyFile/
|   |   ├── CiCopyFile_list.php
|   |   ├── CiCopyFile-form.php
|   |   ├── CiCopyFile_read.php
```

## Output Directory Structure for HMVC Composer Installers Extender

under application/module directory will be
```
CiCopyFile/
├── controllers/
|   ├── CiCopyFile.php
├── models/
|   ├── CiCopyFile_model.php
├── views/
|   ├── CiCopyFile/
|   |   ├── CiCopyFile_list.php
|   |   ├── CiCopyFile-form.php
|   |   ├── CiCopyFile_read.php
```


