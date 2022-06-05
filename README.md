```c#
// This is my README.md
[Header("Welcome to Bitlxn")]
[SerializedField] public string welcomeMsg = "Hey, im Bitlxn";
// Also im a game developer and I mainly work in the Unity Engine, but I have used the Godot Engine before.

private void Start() {
  PrintMsg(welcomeMsg);
}

public void PrintMsg(string printMsg) {
  Debug.Log(printMsg);
}

// Output: Hey, im Bitlxn

```
