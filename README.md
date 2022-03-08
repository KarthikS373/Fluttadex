# flutterista

This application is developed to learn Flutter using Flutter. Different widgets used in Flutter can be viewed in this app along with their implementation, description and code. If you like our work, ⭐ the repository to show support.

# How to contribute to this project

- Make sure to read the [contributing guidelines](CONTRIBUTING.md) before contributing.
- `Fork` this repository.
- `Clone` your fork on local machine.
- Switch to the `master` branch.
- Make a new `branch`, preferably with the feature name.
- Checkout to the new branch with `git checkout <new_branch_name>`
- Do the desired changes and `commit` them with `git commit -m '<a nice commit message here>'`.
- `Push` the change to your fork on GitHub with `git push origin <your_branch_name>`
- Make a `Pull Request` to the master branch in the original repository, i.e. this one.

Note: Make sure you are always up to date with sync and pull upstream. Sync and pull before you start and before you push your work.

### How to contribute to the Widget Catalog

1. Create a new dart file named `*widget*.dart` for the widget being added under `lib/routes/`
2. Create a class named **_Widget_**_Implementation_ and implement the widget
3. Add description of the widget using **_Widget_**_Description_ class in the `*widget*.dart` file
4. Add the code written for the widget in String format using **_Widget_**_Code_ class in the same file
5. Add a new ListTile using the model `WidgetModel` in `lib/widgetList.dart` for the widget
6. In the `WidgetModel`
    - Add an argument `name` and pass the name of the Widget
    - Add an argument `implementaion` and add `*Widget*Implementation()` as the parameter
    - Add an argument `description` and add `*Widget*Description()` as the parameter
    - Add an argument `codeString` and add `*Widget*Code()` as the parameter
    - Add an argument `link` and include link to the official documentation of the widget as the parameter
    - Add an argument `category` and include category of the widget as the parameter