# Notes

## Proptypes

### Array of shape
[https://til.hashrocket.com/posts/ytrzhrpfxk-proptypes-array-of-shape](https://til.hashrocket.com/posts/ytrzhrpfxk-proptypes-array-of-shape)

## Optimization

To test time

```javascript
const startTime = performance.now();

// code 

const endTime = performance.now();
console.log('Took', (endTime - startTime).toFixed(4), 'milliseconds to generate');

Or 
console.log('Took',(endTime-startTime).toFixed(4)/1000,'secondstogenerate');
```

