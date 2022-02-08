#### Key Takeaways

- Not all of the state data in your app needs to be globally accessible (i.e placed in the context). Keep local state to where it’s needed.

- The context may not be practically suitable for an app with frequent state changes if you want to seamlessly avoid the issue of unnecessary components re-rendering.

- Though, we can manage this issue by splitting the context into multiples. But in this case, the different part of the context data should be able to update independently.


#### Quick Tour

>main context file - context.js
>
>main container wrapped by context api in index.js
>
>used contextType in class component TodosList.js
>
>used context consumer in function component TodoItem.js
