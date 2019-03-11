<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="b0f9f-101">In dieser Übung erstellen Sie eine neue Azure AD-Webanwendungs Registrierung mithilfe des Application Registry Portal (ARP).</span><span class="sxs-lookup"><span data-stu-id="b0f9f-101">In this exercise, you will create a new Azure AD web application registration using the Application Registry Portal (ARP).</span></span>

1. <span data-ttu-id="b0f9f-102">Öffnen Sie einen Browser, und navigieren Sie zum [Anwendungs Registrierungs Portal](https://apps.dev.microsoft.com).</span><span class="sxs-lookup"><span data-stu-id="b0f9f-102">Open a browser and navigate to the [Application Registration Portal](https://apps.dev.microsoft.com).</span></span> <span data-ttu-id="b0f9f-103">Melden Sie sich über ein **persönliches Konto** (aka: Microsoft-Konto) oder ein Geschäfts- **oder Schulkonto**an.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-103">Login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="b0f9f-104">Wählen Sie oben auf der Seite **eine APP hinzufügen** aus.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-104">Select **Add an app** at the top of the page.</span></span>

    > [!NOTE]
    > <span data-ttu-id="b0f9f-105">Wenn auf der Seite mehr als eine Schaltfläche **app hinzufügen** angezeigt wird, wählen Sie diejenige aus, die der Liste **konvergierter apps** entspricht.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-105">If you see more than one **Add an app** button on the page, select the one that corresponds to the **Converged apps** list.</span></span>

1. <span data-ttu-id="b0f9f-106">Legen Sie auf der Seite **Anwendung registrieren** den **Anwendungsnamen** in **python Graph Tutorial** fest, und wählen Sie **Erstellen**aus.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-106">On the **Register your application** page, set the **Application Name** to **Python Graph Tutorial** and select **Create**.</span></span>

    ![Screenshot des Erstellens einer neuen app in der APP-Registrierungs Portal-Website](./images/arp-create-app-01.png)

1. <span data-ttu-id="b0f9f-108">Kopieren Sie auf der Seite mit der **python-Diagramm-Lernprogramm Registrierung** im Abschnitt **Eigenschaften** die **Anwendungs-ID** , so wie Sie Sie später benötigen.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-108">On the **Python Graph Tutorial Registration** page, under the **Properties** section, copy the **Application Id** as you will need it later.</span></span>

    ![Screenshot der neu erstellten Anwendungs-ID](./images/arp-create-app-02.png)

1. <span data-ttu-id="b0f9f-110">Scrollen Sie nach unten zum Abschnitt **Anwendungs Geheimnisse** .</span><span class="sxs-lookup"><span data-stu-id="b0f9f-110">Scroll down to the **Application Secrets** section.</span></span>

    1. <span data-ttu-id="b0f9f-111">Wählen Sie **Neues Kennwort generieren**aus.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-111">Select **Generate New Password**.</span></span>
    1. <span data-ttu-id="b0f9f-112">Kopieren Sie im Dialogfeld **Neues Kennwort generiert** den Inhalt des Felds, so wie Sie es später benötigen.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-112">In the **New password generated** dialog, copy the contents of the box as you will need it later.</span></span>

        > [!IMPORTANT]
        > <span data-ttu-id="b0f9f-113">Dieses Kennwort wird nie wieder angezeigt, stellen Sie daher sicher, dass Sie es jetzt kopieren.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-113">This password is never shown again, so make sure you copy it now.</span></span>

    ![Screenshot des Kennworts der neu erstellten Anwendung](./images/arp-create-app-03.png)

1. <span data-ttu-id="b0f9f-115">Scrollen Sie nach unten zum Abschnitt **Plattformen** .</span><span class="sxs-lookup"><span data-stu-id="b0f9f-115">Scroll down to the **Platforms** section.</span></span>

    1. <span data-ttu-id="b0f9f-116">Wählen Sie **Plattform hinzufügen**aus.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-116">Select **Add Platform**.</span></span>
    1. <span data-ttu-id="b0f9f-117">Wählen Sie im Dialogfeld **Plattform hinzufügen** die Option **Web**aus.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-117">In the **Add Platform** dialog, select **Web**.</span></span>

        ![Screenshot Erstellen einer Plattform für die APP](./images/arp-create-app-04.png)

    1. <span data-ttu-id="b0f9f-119">Geben Sie \*\*\*\* im Feld Webplattform die URL `http://localhost:8000/tutorial/callback` für die Umleitungs- **URLs**ein.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-119">In the **Web** platform box, enter the URL `http://localhost:8000/tutorial/callback` for the **Redirect URLs**.</span></span>

        ![Screenshot der neu hinzugefügten Webplattform für die Anwendung](./images/arp-create-app-05.png)

1. <span data-ttu-id="b0f9f-121">Scrollen Sie zum unteren Rand der Seite, und wählen Sie **Speichern**aus.</span><span class="sxs-lookup"><span data-stu-id="b0f9f-121">Scroll to the bottom of the page and select **Save**.</span></span>