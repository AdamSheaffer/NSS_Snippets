# NSS_Snippets

### C&#35; Snippets for NSS night class

To add these to your visual studio, download these .snippet files and add them to the folder:
C:\Users\[USERNAME]\Documents\Visual Studio 2015\Code Snippets\Visual C#\My Code Snippets

Afterwards, go in Visual Studio and hit Ctrl-K, Ctrl-B to get in your code-snippet manager. Make sure that these files
are listed under the "My Code Snippets" folder when viewing Visual C&#35;.

The snippets are:

`testhelp`

```
//Begin Arrange
//End Arrange

//Begin Act
//End Act

//Begin Assert
//End Assert
```

### AND

`testrepo`

```
private Mock<$DbContext$> $mock_context$;

[TestInitialize]
public void Initialize()
{
  $mock_context$ = new Mock<$DbContext$>();
}

[TestCleanup]
public void Cleanup()
{
  $mock_context$ = null;
}
```
