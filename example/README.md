mix run
## in mix.exs:
to add deps add dep at bottom, grab the thingy from hex
```
defp deps do
  [
    {:uuid, "~> 1.1"}
  ]
end
```

also add entry point 
```
def application do
  [
    mod: {Example, []},
    extra_applications: [:logger]
  ]
end
```