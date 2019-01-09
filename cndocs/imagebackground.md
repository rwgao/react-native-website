---
id: imagebackground
title: ImageBackground
---

熟悉web的开发人员的一个常见特性要求是`background-image`。要处理这个用例，您可以使用`<ImageBackground>`组件，它具有与`<Image>`相同的道具，并在其上添加您想要的任何子元素。

在某些情况下，您可能不想使用`<ImageBackground>`，因为实现非常简单。有关更多信息，请参考`<ImageBackground>`[source code](https://github.com/facebook/react-native/blob/master/Libraries/Image/ImageBackground.js)的源代码，并在需要时创建自己的定制组件。

注意，必须指定一些宽度和高度样式属性。

## Example

```javascript
return (
  <ImageBackground source={...} style={{width: '100%', height: '100%'}}>
    <Text>Inside</Text>
  </ImageBackground>
);
```

### Props

* [`Image` props...](image.md#props)
* [`style`](imagebackground.md#style)
* [`imageStyle`](imagebackground.md#imageStyle)
* [`imageRef`](imagebackground.md#imageRef)

---

# Reference

## Props

### `style`

| Type                               | Required |
| ---------------------------------- | -------- |
| [view styles](view-style-props.md) | No       |

### `imageStyle`

| Type                                 | Required |
| ------------------------------------ | -------- |
| [image styles](image-style-props.md) | No       |

### `imageRef`

Allows to set a reference to the inner `Image` component

| Type                                                  | Required |
| ----------------------------------------------------- | -------- |
| [Ref](https://reactjs.org/docs/refs-and-the-dom.html) | No       |
