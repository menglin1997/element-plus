# Infinite Scroll

Load more data while reach bottom of the page

## Basic usage

Add `v-infinite-scroll` to the list to automatically execute loading method when scrolling to the bottom.

:::demo

infinite-scroll/basic

:::

## Disable Loading

:::demo

infinite-scroll/disable-loading

:::

## Directives

| Name                      | Description                                                                                                      | Type     | Accepted values | Default |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------- | -------- | --------------- | ------- |
| v-infinite-scroll         | Load more data while reach bottom of the page                                                                    | function | -               | -       |
| infinite-scroll-disabled  | is disabled                                                                                                      | boolean  | -               | false   |
| infinite-scroll-delay     | throttle delay (ms)                                                                                              | number   | -               | 200     |
| infinite-scroll-distance  | trigger distance (px)                                                                                            | number   | -               | 0       |
| infinite-scroll-immediate | Whether to execute the loading method immediately, in case the content cannot be filled up in the initial state. | boolean  | -               | true    |
