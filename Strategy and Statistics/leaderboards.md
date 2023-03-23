## `?lb`
List a leaderboard of scum holders. By default this will list the three players
with the most scum.

This command takes one optional argument:

| Argument | Description                             |
| -------- | --------------------------------------- |
| Number   | Change the number of results displayed. |

### Examples
```
?lb
```
```
?lb 10
```

## `?bp`
List a leaderboard of battle points. By default this will list the five players
with the most battle points.

This command takes one optional argument:

| Argument | Description                             |
| -------- | --------------------------------------- |
| Number   | Change the number of results displayed. |

### Examples
```
?bp
```
```
?bp 15
```

## `?whobuff`
List a leaderboard of most buffed Kani. By default this will list the ten
players with the most buffs on their rumbler.

This command takes one optional argument:

| Argument | Description                             |
| -------- | --------------------------------------- |
| Number   | Change the number of results displayed. |

### Examples
```
?whobuff
```
```
?whobuff 20
```

## `?inspect`
View the stats of another player’s kani.

This command takes one required and one optional argument:

| Argument      | Description                                                     |
| ------------- | --------------------------------------------------------------- |
| `@playername` | Required, the `@` username of the player you wish to challenge. |
| Role Name     | View stats for the Kani assigned to this role.                  |

### Examples
```
?inspect @Calver
```
```
?inspect @Calver explorer
```

## `?lkani`
Display the base stats of any Kani. 

This command requires one argument:

| Argument  | Description                                                 |
| --------- | ----------------------------------------------------------- |
| Asset ID  | The Algorand ASA ID of the Kani NFT.                        |

### Example
```
?lkani 123456789
```
