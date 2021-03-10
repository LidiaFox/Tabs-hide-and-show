## Tabs JS
This program switch tabs.

1. Take elements. We need _tabs_, _blok with tabs_ and _text/content_.
2. I want to see only one tab on the page, which I choose. That's why I hide all tabs through cycle `for`. I do it use classes css - _remove show and add hide_.
>function hideTabContent(a)

I run function to make it happen.

3. Now I need show class, which I choose. I write the same function just the other way around - _remove hide and add show_, don't use cycle, becouse we know, that show. And first, I check that tab is hidden use `if`.
> function showTabContent(b)

4. Now I need add _Event_. I add object _"event" in function. I create variable `target` and check `if`, that the click was on the element `info-header-tab`. Then I start cycle `for`,  wich matches `target` and tab. Use `function hideTabContent` to hide all tabs, and use `function showTabContent` to show the tab that was clicked.
Use `break` to cycle don't work after fulfilling the condition.




