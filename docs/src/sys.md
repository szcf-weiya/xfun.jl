# System

## Monitor Memory Allocation

```@docs
memuse
```

```@example
for i = 1:3
    a = zeros(1024, 1024, 5, 10);
    memuse()
end
```