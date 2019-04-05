<!-- default file list -->
*Files to look at*:

* [ModuleA.cs](./CS/NavBarAndPrism.ModuleA/ModuleA.cs) (VB: [ModuleA.vb](./VB/NavBarAndPrism.ModuleA/ModuleA.vb))
* [ModuleAView.xaml](./CS/NavBarAndPrism.ModuleA/ModuleAView.xaml) (VB: [ModuleAView.xaml](./VB/NavBarAndPrism.ModuleA/ModuleAView.xaml))
* [ModuleAView.xaml.cs](./CS/NavBarAndPrism.ModuleA/ModuleAView.xaml.cs) (VB: [ModuleAView.xaml.vb](./VB/NavBarAndPrism.ModuleA/ModuleAView.xaml.vb))
* [ModuleB.cs](./CS/NavBarAndPrism.ModuleB/ModuleB.cs) (VB: [ModuleB.vb](./VB/NavBarAndPrism.ModuleB/ModuleB.vb))
* [ModuleBView.xaml](./CS/NavBarAndPrism.ModuleB/ModuleBView.xaml) (VB: [ModuleBView.xaml](./VB/NavBarAndPrism.ModuleB/ModuleBView.xaml))
* [ModuleBView.xaml.cs](./CS/NavBarAndPrism.ModuleB/ModuleBView.xaml.cs) (VB: [ModuleBView.xaml.vb](./VB/NavBarAndPrism.ModuleB/ModuleBView.xaml.vb))
* [NavBarAndPrismTestPage.aspx](./CS/NavBarAndPrism.Web/NavBarAndPrismTestPage.aspx) (VB: [NavBarAndPrismTestPage.aspx](./VB/NavBarAndPrism.Web/NavBarAndPrismTestPage.aspx))
* [Silverlight.js](./CS/NavBarAndPrism.Web/Silverlight.js) (VB: [Silverlight.js](./VB/NavBarAndPrism.Web/Silverlight.js))
* [Bootstrapper.SL.cs](./CS/NavBarAndPrism/Bootstrapper.SL.cs) (VB: [Bootstrapper.SL.vb](./VB/NavBarAndPrism/Bootstrapper.SL.vb))
* [Bootstrapper.WPF.cs](./CS/NavBarAndPrism/Bootstrapper.WPF.cs) (VB: [Bootstrapper.WPF.vb](./VB/NavBarAndPrism/Bootstrapper.WPF.vb))
* [NavBarControlAdapter.cs](./CS/NavBarAndPrism/NavBarControlAdapter.cs) (VB: [NavBarControlAdapter.vb](./VB/NavBarAndPrism/NavBarControlAdapter.vb))
* [Shell.xaml](./CS/NavBarAndPrism/Shell.xaml) (VB: [Shell.xaml](./VB/NavBarAndPrism/Shell.xaml))
* [Shell.xaml.cs](./CS/NavBarAndPrism/Shell.xaml.cs) (VB: [Shell.xaml.vb](./VB/NavBarAndPrism/Shell.xaml.vb))
<!-- default file list end -->
# How to define NavBarGroups in different modules with Prism


<p>This example defines two modules with NavBarGroup objects. The modules are injected into NavBarControl using a NavBarControlAdapter object.<br />
NavBarControlAdapter sets the NavBarControl.ItemsSource property to a collection of Views (each of which is a NavBarGroup object).</p>

<br/>


