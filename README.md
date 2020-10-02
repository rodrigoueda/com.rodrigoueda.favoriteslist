# Favorites List

## Credits

This package is a fork from the original  [BrokenVector/favorites-list](https://github.com/BrokenVector/favorites-list) repository.

The original plugin is also available in the [Unity Assetstore](https://assetstore.unity.com/packages/tools/utilities/favorites-list-72293).

### Review video
[![Original plugin review video](https://img.youtube.com/vi/5UGga__0_es/0.jpg)](https://www.youtube.com/watch?v=5UGga__0_es)

You can check out the review to the original plugin [here](https://www.youtube.com/watch?v=5UGga__0_es).

The two main changes from this version to the original are:
- Support to multiple favorites list files;
- Support to [Unity Package Manager](https://docs.unity3d.com/Manual/Packages.html).

## Installation

<https://docs.unity3d.com/Packages/com.unity.package-manager-ui@2.1/manual/index.html>

```json
{
    "dependencies": {
        "com.rodrigoueda.favoriteslist": "https://github.com/rodrigoueda/com.rodrigoueda.favoriteslist.git#1.0.0"
    }
}
```

## Usage

To open the window, just navigate to Tools -> Favorites List.

The first time you open this window, press the button **Create a Favorites List** to create a new profile.

![Create a Favorites List](https://gist.githubusercontent.com/rodrigoueda/c6a714d7cbbdc58641b89679e06d5efb/raw/bc17c2f880024af2185393e8d4cf0a3d9b9e67cc/FavoritesList_CreateYourFirstList.png)

After that, you can create additional profile pressing the **"+"** button.
To alternate betweeen profiles, use the dropdown.

![Create a Favorites List](https://gist.githubusercontent.com/rodrigoueda/c6a714d7cbbdc58641b89679e06d5efb/raw/bc17c2f880024af2185393e8d4cf0a3d9b9e67cc/FavoritesList_DropdownSelection.png)

![Screenshot](https://assetstorev1-prd-cdn.unity3d.com/key-image/b6776f4c-d51e-459b-bfd9-1d255e27b66d.webp)

Just drop your favorite objects onto the list. If you quickly want to access them, click on its button in the list and the object will be selected (and pinged).

The following objects are supported:
- Folders
- All assets / objects in the project view (like prefabs)
- GameObjects
So basically everything which is a UnityEngine.Object.

The search works exactly like the Unity search (type search supported).
E.g. "t:Camera" gives you a list with GameObjects containing the Camera component.
