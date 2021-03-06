1. You're going to make an app with a big button and a surprise message when you press it! Go to App Inventor and select "Start a new project" from the **Projects** menu. Give your project a name.

2. In the **Palette** on the left, click **Layout** and drag a **VerticalArrangement** onto the phone screen.
 
3. In the **Properties** pane on the right, click on the **Height** property, select **Fill parent** and click **OK**. Do the same for the **Width** property. 

4. Now look in the **Palette** under **User Interface** and drag a **Button** onto your **VerticalArrangement** on the phone screen.

5. Over on the right, under **Components**, click on the `VerticalArrangement1` component. In the **Properties** pane, change the **AlignHorizontal** and **AlignVertical** both to _Center_. Did you see the button move to the middle of the phone screen?
   ![](VertArrAlignProps2_258_850.png)
   
6. Select `Button1` and in the **Properties**, scroll down and change the **Text** to "Do not press". If you want, change the **BackgroundColor** and various **Font** properties too.
   ![](ButtonPropsFont_290_900.png)
   
7. Change the **Height** and **Width** properties to `150` **pixels** and change the **Shape** to **oval**.

8. Click the **Add Screen** button near the top of the page. Leave the name as Screen2 and click **OK**.

9. When the new screen loads, find the **Label** component under **User Interface** in the Palette and drag it onto the screen. Under **Properties**, change the **Text** to "This app will self destruct in 5 seconds".

10. Under **Sensors** in the **Palette**, find the **Clock** and drag it onto the screen. It's an invisible component, so you won't see it on the screen. In the **Properties**, change the **TimerInterval** to `5000`.

11. Click **Blocks** in the top right. Click on `Clock1` and take out the `When Clock1.Timer do` block. Now click **Control** under the **Built-in** blocks, grab the `close application` block and snap it into your other block.
    ![](TimerBlock_124_800.png)
    
12. Switch to `Screen1` by selecting it from the button near the top.

13. Add the following blocks from **Button1** and **Control**.
    ![](Button1BlocksA_79_800.png)
    
14. Under **Built-in** select **Text** take the empty text block \(you might have to scroll up, it's at the very top\) and snap it into place. Click inside it and type "Screen2".
   ![](Button1BlocksB_73_800.png)
   
15. Your app is done! Try it out using the Emulator under **Connect** in the menu or select QR Code option under **Build** to get a link to install the app on your Android device.
 * **Note:** To install via QR Code you need to turn on "Allow installation of apps from unknown sources" on your Android device.
    ![](Button_160_800.png) 
![](whitespace_70_800.png)

{% callout %}<span style="color: #000000; margin-right: 10px;">This is just the beginning! Learn how to make a quiz in the Beginner App Inventor Sushi Cards at <b>http://dojo.soy/mini-apps-begin</b>, and earn<br /> a digital badge too! To see this card online or print out more, go to <b>http://dojo.soy/mini-sushi-appinv</b> </span>
{% endcallout %}







