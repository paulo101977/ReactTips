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

#### Auto invoke anonymous function ES6:

```javascript
  (()=>{ console.log('just for test!') })()
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
