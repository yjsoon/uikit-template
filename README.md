# UIKit App (No Storyboard): an Xcode template

An Xcode project template for UIKit apps that build their screens in code. It's Apple's iOS App template with the storyboard taken out. `SceneDelegate` creates the window and shows `ViewController`, and `ViewController` has a `#Preview` so you can see your changes without running the app.

We use it in Tinkercademy's iOS in UIKit course. It's made for Xcode 27.

## Install

Open Terminal, paste this line, and press Return:

```
git clone https://github.com/yjsoon/uikit-template.git ~/Library/Developer/Xcode/Templates/Project\ Templates/Tinkercademy
```

Then quit Xcode (Cmd-Q) and open it again.

## Use

1. Click the arrow next to **New Project**, then **Choose Template…**.
2. Stay on the **iOS** tab and scroll down to the **Tinkercademy** section.
3. Pick **UIKit App (No Storyboard)**, and fill in the options as usual.

## Update

```
git -C ~/Library/Developer/Xcode/Templates/Project\ Templates/Tinkercademy pull
```

## Remove

Delete the `Tinkercademy` folder inside `~/Library/Developer/Xcode/Templates/Project Templates/`, then restart Xcode.
