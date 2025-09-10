# DesignPatterns.Creational.FactoryMethod

## Intent
Define an interface (`Product`) for creating an object, but let **subclasses decide which class to instantiate**. The Factory Method pattern promotes **flexibility** and **extensibility** by decoupling object creation from usage.

---

## UML Diagram

Below is the class diagram for the Factory Method pattern:

![Factory Method UML](https://uml.planttext.com/plantuml/svg/fLHBRi8m4Dr7oXr6R0ggo04GgY0WkggAUeF16OBLn1FPatvKUg8UeJjErZW9296gj6NfyNjltfknF762Liey2mFHaX4iK0dRLxWZsN02_LjU3608imoTWxd6r68U1c5Ge7h4bA0t9wTJiqGHiiP5CqiecWrcKIlLAFNWBGm0jAbWQrG4Iyj9gQGf0rnpGRPczWSZU6AT-FgxRmMWwkupDigIKCkSWiwBZ78ouYvNY_-hXYidjagwb_NvsHwew-CXU7ghtLuxpkd-rrvRyIdGYv19_jRj9yNu4iKhUA2i3k0skd2-j5U9efl3C4Um-r2-JcxtMODEKtbqPyddQF5tjBXBsziORwEeq-KS83uEDTuEXntpvm1nCol3Gc1rkX7WzPxGZFhaAK3foC79-1kaCF1AK1l0W-jdNI7AzbafBejCczGZiJerJfhLHnvIhRgs4WRr3YVLkVu3lW00)

> Clicking or viewing this file on GitHub will render the diagram inline.

---

## Problem
Client code often instantiates concrete classes directly:

```csharp
var button = new WindowsButton();
button.Render();
