---
order: 0
title:
  zh-CN: 按钮类型
  en-US: Type
---

## zh-CN

按钮有四种类型：主按钮、次按钮、虚线按钮、危险按钮。主按钮在同一个操作区域最多出现一次。

## en-US

There are Round Edges Button

````jsx
import { Button } from 'antd';

ReactDOM.render(
  <div>
    <Button roundEdges block type="primary">Primary</Button>
    <Button roundEdges>Default</Button>
    <Button roundEdges type="dashed">Dashed</Button>
    <Button roundEdges type="danger">Danger</Button>
  </div>,
  mountNode
);
````
