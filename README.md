# Titled Project Tabs Documentation

<img width="600" height="315" alt="image" src="https://github.com/user-attachments/assets/59d012d1-5a1c-47ff-be16-9aad5d56976f" />

<br><br>
## Overview
Titled Project Tabs (TPT) is the Unity Editor extention asset that handles naming of multiple Project type editor tabs.

<br><br>
## Usage and settings

### Installation

Import the package into Unity Project via Package Manager, or [TPT Unity Asset Store page](https://assetstore.unity.com/packages/slug/361738).
<br><br>
### Important notes

TPT is working with *Two Column Layout* Project tabs only. Layout can be set in Project tab's Properties dropdown:<br>

<img width="508" height="228" alt="2 col" src="https://github.com/user-attachments/assets/dfd97982-c679-4e8d-9cd9-7aa6693dd755" />
<br><br>

*Default* and *Locked* tabs are titled with 2 separate modes. Switch the lock state on the Project tab's *Lock* button:<br>

<img width="456" height="229" alt="lock" src="https://github.com/user-attachments/assets/c90ea315-2488-4a59-9b1e-98de11d51db8" />
<br><br><br>

### Settings window

Use the shortcut to the Settings asset located at the *Top Menu/Window/Titled Project Tabs Settings*":<br>

<img width="253" height="518" alt="menu item" src="https://github.com/user-attachments/assets/01f6044e-606e-4850-8eb1-283ac4fc4b48" />
<br><br>

TPT Settings window:<br>

<img width="240" height="138" alt="image" src="https://github.com/user-attachments/assets/48dbd352-b84e-440f-afb7-f6065095e4f1" />
<br><br><br>

### Titling modes overview and examples

The following examples will show the Project tab of example folder: *Assets/TPT/Nested Folder/Nested Folder 2*
<br><br><br>

#### Fixed Mode

Swap the initial "Project" line with fixed title.

>**Settings**
>Mode: Fixed<br>
>Title: Fixed Name<br>
><img width="512" height="226" alt="image" src="https://github.com/user-attachments/assets/f5d2fc55-14f3-4363-aca1-d1708d9cad37" />

<br><br>

#### Folder Only Mode

Keep the active folder name as the tab title.

>**Settings**
>Mode: Folder Only<br>
><img width="512" height="226" alt="image" src="https://github.com/user-attachments/assets/1d37e03a-8ff6-4997-b7bc-9802ef329dd4" />

<br><br>

#### Shrink Mode

Shrink the active folder path to selected amount of symbols (if needed).
Optional parameter *Use Prefix* alters the first 2 symbols with dots in case of shrinking.

>Mode: Shrink<br>
>Max Length: 20<br>
>Use prefix: true<br>
><img width="512" height="226" alt="image" src="https://github.com/user-attachments/assets/76f89f60-3656-43f9-b688-4113c6a7ec59" />

<br><br>

#### Wrap Mode

Wraps the active folder path keeping the top-level folder and the active folder name in title.

>Mode: Wrap<br>
><img width="512" height="226" alt="image" src="https://github.com/user-attachments/assets/1fc0c3f5-24a1-4dd5-8c53-28c62f585e3c" />

<br><br>

#### Regex Mode

Allows to use the custom Regex pattern to create the tab title. Invalid parameters will result in *[Invalid Regex Properties]* titles.

>Mode: Regex<br>
>Regex Pattern:Assets\/.*\/(.+)<br>
>Replacement: A/.../$1<br>
><img width="512" height="226" alt="image" src="https://github.com/user-attachments/assets/d2973c7d-afb4-4ad5-a936-016752417838" />

<br><br>

[GitHub docs](https://github.com/SergeyDoes/Titled-Project-Tabs-Documentation)<br>
[SergeyDoes](https://github.com/SergeyDoes)
