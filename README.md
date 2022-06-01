## JsonMessageBuilder

## Qu'est-ce qu'est ?

C'est une classe java "utilitaire" qui va vous permettre de faire des messages json (cliquable par exemple) beaucoup plus facilement.

## Utilisations

```java
p.spigot().sendMessage(new JsonMessageBuilder("")
                    .setText("§fGit§3Hub§7: §6NekEau")
                    .setHoverEvent(new HoverEvent(HoverEvent.Action.SHOW_TEXT, new ComponentBuilder("§7§oClique ici .").create()))
                    .setClickEvent(new ClickEvent(ClickEvent.Action.OPEN_URL, "https://github.com/NekEau/"))
                    .build());
```
