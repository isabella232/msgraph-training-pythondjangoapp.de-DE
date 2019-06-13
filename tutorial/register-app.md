<!-- markdownlint-disable MD002 MD041 -->

<span data-ttu-id="8d69f-101">In dieser Übung erstellen Sie mithilfe des Azure Active Directory Admin Center eine neue Azure AD-Webanwendungs Registrierung.</span><span class="sxs-lookup"><span data-stu-id="8d69f-101">In this exercise, you will create a new Azure AD web application registration using the Azure Active Directory admin center.</span></span>

1. <span data-ttu-id="8d69f-102">Öffnen Sie einen Browser, und navigieren Sie zum [Azure Active Directory Admin Center](https://aad.portal.azure.com).</span><span class="sxs-lookup"><span data-stu-id="8d69f-102">Open a browser and navigate to the [Azure Active Directory admin center](https://aad.portal.azure.com).</span></span> <span data-ttu-id="8d69f-103">Melden Sie sich mit einem **persönlichen Konto** (auch: Microsoft-Konto) oder einem **Geschäfts- oder Schulkonto** an.</span><span class="sxs-lookup"><span data-stu-id="8d69f-103">Login using a **personal account** (aka: Microsoft Account) or **Work or School Account**.</span></span>

1. <span data-ttu-id="8d69f-104">Wählen Sie in der linken Navigationsleiste **Azure Active Directory** aus, und wählen Sie dann **App** -Registrierungen unter **Manage**aus.</span><span class="sxs-lookup"><span data-stu-id="8d69f-104">Select **Azure Active Directory** in the left-hand navigation, then select **App registrations** under **Manage**.</span></span>

    ![<span data-ttu-id="8d69f-105">Ein Screenshot der APP-Registrierungen</span><span class="sxs-lookup"><span data-stu-id="8d69f-105">A screenshot of the App registrations</span></span> ](./images/aad-portal-app-registrations.png)

1. <span data-ttu-id="8d69f-106">Wählen Sie **Neue Registrierung** aus.</span><span class="sxs-lookup"><span data-stu-id="8d69f-106">Select **New registration**.</span></span> <span data-ttu-id="8d69f-107">Legen Sie auf der Seite **Anwendung registrieren** die Werte wie folgt fest.</span><span class="sxs-lookup"><span data-stu-id="8d69f-107">On the **Register an application** page, set the values as follows.</span></span>

    - <span data-ttu-id="8d69f-108">Legen Sie **Name** auf `Python Graph Tutorial` fest.</span><span class="sxs-lookup"><span data-stu-id="8d69f-108">Set **Name** to `Python Graph Tutorial`.</span></span>
    - <span data-ttu-id="8d69f-109">Legen Sie **Unterstützte Kontotypen** auf **Konten in allen Organisationsverzeichnissen und persönliche Microsoft-Konten** fest.</span><span class="sxs-lookup"><span data-stu-id="8d69f-109">Set **Supported account types** to **Accounts in any organizational directory and personal Microsoft accounts**.</span></span>
    - <span data-ttu-id="8d69f-110">Legen Sie unter **Umleitungs-URI** die erste Dropdownoption auf `Web` fest, und legen Sie den Wert auf `http://localhost:8000/tutorial/callback` fest.</span><span class="sxs-lookup"><span data-stu-id="8d69f-110">Under **Redirect URI**, set the first drop-down to `Web` and set the value to `http://localhost:8000/tutorial/callback`.</span></span>

    ![Screenshot der Seite "Anwendung registrieren"](./images/aad-register-an-app.png)

1. <span data-ttu-id="8d69f-112">Wählen Sie **Registrieren** aus.</span><span class="sxs-lookup"><span data-stu-id="8d69f-112">Choose **Register**.</span></span> <span data-ttu-id="8d69f-113">Kopieren Sie auf der Seite **python Graph Tutorial** den Wert der **Anwendungs-ID (Client)** , und speichern Sie ihn, und Sie benötigen ihn im nächsten Schritt.</span><span class="sxs-lookup"><span data-stu-id="8d69f-113">On the **Python Graph Tutorial** page, copy the value of the **Application (client) ID** and save it, you will need it in the next step.</span></span>

    ![Ein Screenshot der Anwendungs-ID der neuen App-Registrierung](./images/aad-application-id.png)

1. <span data-ttu-id="8d69f-115">Wählen Sie unter **Verwalten** die Option **Zertifikate und Geheime Clientschlüssel** aus.</span><span class="sxs-lookup"><span data-stu-id="8d69f-115">Select **Certificates & secrets** under **Manage**.</span></span> <span data-ttu-id="8d69f-116">Wählen Sie die Schaltfläche **Neuen geheimen Clientschlüssel** aus.</span><span class="sxs-lookup"><span data-stu-id="8d69f-116">Select the **New client secret** button.</span></span> <span data-ttu-id="8d69f-117">Geben Sie einen Wert unter **Beschreibung** ein, wählen Sie eine der Optionen für **Gilt bis** aus, und wählen Sie dann **Hinzufügen**.</span><span class="sxs-lookup"><span data-stu-id="8d69f-117">Enter a value in **Description** and select one of the options for **Expires** and choose **Add**.</span></span>

    ![Screenshot des Dialogfelds zum Hinzufügen eines geheimen Client Schlüssels](./images/aad-new-client-secret.png)

1. <span data-ttu-id="8d69f-119">Kopieren Sie den Wert des geheimen Clientschlüssels, bevor Sie diese Seite verlassen.</span><span class="sxs-lookup"><span data-stu-id="8d69f-119">Copy the client secret value before you leave this page.</span></span> <span data-ttu-id="8d69f-120">Sie benötigen ihn im nächsten Schritt.</span><span class="sxs-lookup"><span data-stu-id="8d69f-120">You will need it in the next step.</span></span>

    > [!IMPORTANT]
    > <span data-ttu-id="8d69f-121">Dieser geheime Clientschlüssel wird nicht noch einmal angezeigt, stellen Sie daher sicher, dass Sie ihn jetzt kopieren.</span><span class="sxs-lookup"><span data-stu-id="8d69f-121">This client secret is never shown again, so make sure you copy it now.</span></span>

    ![Screenshot des neu hinzugefügten geheimen Client Schlüssels](./images/aad-copy-client-secret.png)
