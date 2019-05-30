# Templates for Visual Studio C#
## Table of Contents
1. [Projec Template](#Projec-Template)
2. [Code Snippets](#Code-Snippets)

## Projec Template

Template for Simple WPF Application prepard with some usefull frameworks. Caliburn Micro for mvvm with Autofac and for a pretty look and feel MaterialDesignThemes for wpf.

### Folder structure informations

Organistaion of each View together with its ViewModel and Model in the same namespace.
e.g. XHome contains all the View, ViewModel and the Model. 

### Used NuGets

- Autofac
- Autofac.log4net
- Caliburn.Micro
- MaterialDesignColors
- MaterialDesignThems
- Stateless

## Code Snippets
Copy the snippet into the installaiton folder of your VS.
### Caliburn Micro
#### Property
Type `cmprop` for using the code snippet
`public int Login { get => _login; set{ _login = value; NotifyOfPropertyChange(nameof(Login)); }}`

