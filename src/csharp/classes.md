# C# Classes

```csharp
namespace YourNamespace.Cars;

public class Camaro {
    private int _hp;
    private bool _isRunning;

    public Camaro(int hp) {
        _hp = hp;
        _isRunning = false;
    }

    public void StartEngine() {
        _isRunning = true;
    }

    public HP => _hp;

    public IsRunning = _isRunning;
}
```