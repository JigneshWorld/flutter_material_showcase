# flutter_material_showcase

Material Design components showcase for Flutter apps.

This project is a rip-off of Ataul's [Material Design Components Showcase](https://github.com/ataulm/material-design-components-showcase) Android project, but in Flutter!

You can use this Flutter package to preview your `ThemeData` and see how it looks like with different Material Widgets.

## Usage

1. Include the library in your project `pubspec.yaml`:

```
todo
```

2. Add the `MaterialShowcase` Widget somewhere in your app:

```
MaterialApp(
  title: 'Flutter Demo',
  theme: ThemeData(
        brightness: brightness,
        primarySwatch: Colors.blue,
  ),
  home: Scaffold(
    body: ListView(
      children: <Widget>[
        MaterialShowcase(),
      ],
    ),
  ),
);
```

3. Play with the different parameters in `ThemeData` and see how it looks like.

## License

```
TODO
```



