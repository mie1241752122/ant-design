---
order: 2
title:
  zh-CN: 倒计时
  en-US: Countdown
---

## zh-CN

倒计时子组件。

## en-US

Sub Countdown component.

```jsx
import { Statistic, Row, Col } from 'antd';

const Countdown = Statistic.Countdown;
const deadline = Date.now() + 1000 * 60 * 60 * 24 * 2 + 1000 * 30; // Moment is also OK

ReactDOM.render(
  <Row gutter={16}>
    <Col span={12}>
      <Countdown title="Countdown" value={deadline} />
    </Col>
    <Col span={12}>
      <Countdown title="Million Seconds" value={deadline} format="HH:mm:ss:SSS" />
    </Col>
    <Col span={24}>
      <Countdown title="Day Level" value={deadline} format="D 天 H 时 m 分 s 秒" />
    </Col>
  </Row>,
  mountNode
);
```