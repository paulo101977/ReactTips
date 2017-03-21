# ReactTips
This is my personal tips for React use

## React comments inside ES6 code:

```javascript
render({
  <div>
    {/* this is a comment inside React components */}
  </div>
})
```

## Render element with function anonymous:
```javascript
render({
  <div>
    {
      (
        () => 
        {
          <ElementDemo></ElementDemo>
        }
      )() 
    }
  </div>
})
```
