# ShellAppSample
Xamarin Forms - Menu - Shell Form App with FontAwesome Icons.

I made a very simple sample that I did taken a code base from
https://www.thewissen.io/introducing-xamarin-ui-july
in this post, Steven provides multiple samples of UI in Xamarin Forms.

<p align="center">
  <img src="https://github.com/DgarciarDev/ShellAppSample/blob/master/ShellAppSample/ShellAppSample/Sample.gif" width="250" title="hover text">
</p>

## Using FontImageSource

Finally, I change the "icon=" property with <ShellContent.Icon>tag and create a <FontImageSource> tag and include those parameters that I need: 

FontFamily, Color, Glyph and Size (in my case).

- FontImageSource in action:

Route in AppShell.xaml

## Important:

I should include the x:Key "FontAwesome5FreeSolid" with the font selected (fontawesome_solid.otf) in the aplication.resources in App.Xaml File.
