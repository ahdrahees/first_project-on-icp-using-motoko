# Motoko first_project

    Here in this project contain a *greet()* function which returns any text that we input, and this function is inside the canister named *first_canister*

## main.mo

    Installed code inside the canister.

```motoko
actor {
  public query func greet(name : Text) : async Text {
    return "Hello " # name # "!";
  };
};
```
