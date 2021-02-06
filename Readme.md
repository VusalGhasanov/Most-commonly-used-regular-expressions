# Most Commonly used regular expression

### 1. Checks login

```

^[a-zA-Z][a-zA-Z0-9-_\.]{1,20}$

```

### 2. Checks site domain

```

/^(http|https|ftp)://([A-Z0-9][A-Z0-9_-]*(?:.[A-Z0-9][A-Z0-9_-]*)+):?(d+)?/?/i

```

### 3. Checks md5 hash

```

/^[a-f0-9]{32}$/

```

### 4. Checks 16 bit color palette

```

/^#(?:(?:[a-fd]{3}){1,2})$/i

```


### 5. Checks IPv4 address

```

((25[0-5]|2[0-4]\d|[01]?\d\d?)\.){3}(25[0-5]|2[0-4]\d|[01]?\d\d?)

```

### 6. Checks IPv6 address

```

((^|:)([0-9a-fA-F]{0,4})){1,8}$

```


### 7. Checks MAC address

```

([0-9a-fA-F]{2}([:-]|$)){6}$|([0-9a-fA-F]{4}([.]|$)){3}

```

### 8. Checks date formart (YYYY-MM-DD)

```

[0-9]{4}-(0[1-9]|1[012])-(0[1-9]|1[0-9]|2[0-9]|3[01])

```

### 9. Checks date formart (DD/MM/YYYY)

```

(0[1-9]|[12][0-9]|3[01])[- /.](0[1-9]|1[012])[- /.](19|20)\d\d

```

### 10. Checks time formart (HH:MM:SS )

```

^([0-1]\d|2[0-3])(:[0-5]\d){2}$

```
