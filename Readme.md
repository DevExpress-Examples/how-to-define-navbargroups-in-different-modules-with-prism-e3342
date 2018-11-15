<!-- default file list -->
*Files to look at*:

* [Bootstrapper.WPF.cs](./CS/NavBarAndPrism/Bootstrapper.WPF.cs) (VB: [Bootstrapper.WPF.vb](./VB/NavBarAndPrism/Bootstrapper.WPF.vb))
* **[Shell.xaml](./CS/NavBarAndPrism/Shell.xaml) (VB: [Shell.xaml](./VB/NavBarAndPrism/Shell.xaml))**
<!-- default file list end -->
# How to define NavBarGroups in different modules with Prism


<p>This example defines two modules with NavBarGroup objects. The modules are injected into NavBarControl using a NavBarControlAdapter object.<br />
NavBarControlAdapter sets the NavBarControl.ItemsSource property to a collection of Views (each of which is a NavBarGroup object).</p>

<br/>


