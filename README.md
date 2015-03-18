KeyboardVisibilityEvent
===

Android Library to handle soft keyboard visibility change event.
show/hide keyboard method is also included.

## Features
- handle keyboard visibility change
- check if keyboard is currently visible
- show/hide keyboard(check UIUtil.java)

## Usage

check out sample project!


### Add event listener for keyboard change event

```java
KeyboardVisibilityEvent.setEventListener(
        getActivity(),
        new KeyboardVisibilityEventListener() {
            @Override
            public void onVisibilityChanged(boolean isOpen) {
                // some code depending on keyboard visiblity status
            }
        });
```

## License

http://www.apache.org/licenses/LICENSE-2.0.txt

