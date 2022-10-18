# state-management
前端框架中的狀態管理的理解和使用

我在2022年7月之前，做了兩年多的React框架的項目，從React的作者或者是社區內的一些活躍成員，老師那里收集來收集了不少關于狀態管理的理解和實踐方法。現在我換到Angular框架后，也面臨著組件前通訊和狀態管理的需要，覺得有一些之前了解的概念可以拿來做參照，再結合Angular的機制看看，是不是可以使用同樣的思路。

### 一、關于組件間的通訊
TL/DR: 組件間的通訊的最推崇的方式是傳遞參數`<Calender disabledDate={[new Date('2022-01-01'), new Date('2022-03-01')]} onDateSelected={handleDateSelected}/>`。

組件間的數據傳遞有如下這幾種方式：
1. 組件參數 (props)
2. 上下文API (Context)
3. 直接訪問組件內的方法 (useImperativeHandle)
4. 第三方的狀態管理庫，按實現的方式可分為，數據放在React和放在React外的兩種 (Redux的數據是放在React內，zustand的數據是放在React外)。

未完成。。。
