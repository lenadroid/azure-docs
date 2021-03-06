## Create an IoT hub
Create an IoT hub for your simulated device app to connect to. The following steps show you how to complete this task by using the Azure portal.

1. Sign in to the [Azure portal][lnk-portal].

1. Select **New** > **Internet of Things** > **IoT Hub**.
   
    ![Azure portal Jumpbar][1]

1. In the **IoT hub** pane, enter the following information for your IoT hub:

   * **Name**: Create a name for your IoT hub. If the name you enter is valid, a green check mark appears.

   [!INCLUDE [iot-hub-pii-note-naming-hub](iot-hub-pii-note-naming-hub.md)]

   * **Pricing and scale tier**: For this tutorial, select the **F1 - Free** tier. For more information, see the [Pricing and scale tier][lnk-pricing].

   * **Resource group**: Create a resource group to host the IoT hub or use an existing one. For more information, see [Use resource groups to manage your Azure resources][lnk-resource-groups]

   * **Location**: Select the closest location to you.

   * **Pin to dashboard**: Check this option for easy access to your IoT hub from the dashboard.

    ![IoT hub window][2]

1. Click **Create**. Your IoT hub might take a few minutes to create. You can monitor the progress in the **Notifications** pane.

1. When your new IoT hub is ready, click its tile in the Azure portal to open its properties window. Now that you have created an IoT hub, locate the important information that you use to connect devices and applications to your IoT hub. Make a note of the **Hostname**, and then click **Shared access policies**.
   
    ![New IoT hub window][4]

1. In **Shared access policies**, click the **iothubowner** policy, and then make note of the IoT Hub connection string in the **iothubowner** window. For more information, see [Access control][lnk-access-control] in the "IoT Hub developer guide."
   
    ![Shared access policies][5]

<!-- Images. -->
[1]: ./media/iot-hub-get-started-create-hub/create-iot-hub1.png
[2]: ./media/iot-hub-get-started-create-hub/create-iot-hub2.png
[4]: ./media/iot-hub-get-started-create-hub/create-iot-hub4.png
[5]: ./media/iot-hub-get-started-create-hub/create-iot-hub5.png

<!-- Links -->
[lnk-access-control]: ../articles/iot-hub/iot-hub-devguide-security.md
[lnk-portal]: https://portal.azure.com/
[lnk-pricing]: https://azure.microsoft.com/pricing/details/iot-hub/
[lnk-resource-groups]: ../articles/azure-resource-manager/resource-group-portal.md
