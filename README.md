React Coverflow
===
Fork of React Coverflow with an onChange event.  
https://github.com/andyyou/react-coverflow  
  
Install with: `yarn add git+https://github.com/alana314/react-coverflow-callback
`

Usage:  
```
<Coverflow width="960" height="500" classes={{background: 'rgb(233, 23, 23)'}} className=''
    displayQuantityOfSide={2}
    navigation={false}
    enableScroll={true}
    clickable={true}
    active={0}
    onChange={(active) => console.log('onChange', active)}
  >
```
