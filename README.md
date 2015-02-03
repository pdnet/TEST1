@{
    ViewBag.Title = "CQMS Home";
}

<!DOCTYPE html>
<html>

<body class="metro">
    <br />

    <div class="master">
     
            <div class="tile bg-darkPink">
                <div class="tile-content icon">
                    <i class="icon-dashboard"></i>
                </div>
                <div class="tile-status">
                    <span class="name">Domain</span>
                </div>
            </div>
    
        <div class="tile bg-darkIndigo" >
            <div class="tile-content icon">
                <i class="icon-tree-view"></i>
            </div>
            <div class="tile-status">
                <span class="name">Category</span>
            </div>
        </div>
        <div class="tile bg-darkOrange">
            <div class="tile-content icon">
                <i class="icon-flag-2"></i>
            </div>
            <div class="tile-status">
                <span class="name">Sub Category</span>
            </div>
        </div>
        <div class="tile bg-lightOlive">
            <div class="tile-content icon">
                <i class="icon-blocked"></i>
            </div>
            <div class="tile-status">
                <span class="name">Criticality</span>
            </div>
        </div>
        <div class="tile bg-crimson">
            <div class="tile-content icon">
                <i class="icon-grid-view"></i>
            </div>
            <div class="tile-status">
                <span class="name">Check Points</span>
            </div>
        </div>
        <div class="tile bg-darkEmerald" onclick="window.location='@Url.Action("CheckListMaster", "Home")';">
            <div class="tile-content icon">
                <i class="icon-checkbox"></i>
            </div>
            <div class="tile-status">
                <span class="name">Check List</span>
            </div>
        </div>
        <div class="tile bg-cobalt">
            <div class="tile-content icon">
                <i class="icon-user-2"></i>
            </div>
            <div class="tile-status">
                <span class="name">User Preference</span>
            </div>
        </div>
        <div class="tile bg-pink" onclick="window.location='@Url.Action("AdminPanel", "Home")';">
            <div class="tile-content icon">
                <i class="icon-tools"></i>
            </div>
            <div class="tile-status">
                <span class="name">Admin Panel</span>
            </div>
        </div>
    </div>
    <br />
    <br />
    <br />

    <div class="transaction">
        <div class="tile bg-darkGreen" onclick="window.location='@Url.Action("CheckListCreation", "CheckList")';">
            <div class="tile-content icon">
                <i class="icon-clipboard-2"></i>
            </div>
            <div class="tile-status">
                <span class="name">Generate Check List</span>
            </div>
        </div>
        <div class="tile bg-darkTeal" onclick="window.location='@Url.Action("CheckListUpdation", "CheckList")';">
            <div class="tile-content icon">
                <i class="icon-zip-2"></i>
            </div>
            <div class="tile-status">
                <span class="name">Check List Feedback</span>
            </div>
        </div>

    </div>

    <br />
    <br />
    <br />

    <div class="reports">
        <div class="tile bg-darkIndigo">
            <div class="tile-content icon">
                <i class="icon-paragraph-center"></i>
            </div>
            <div class="tile-status">
                <span class="name">Reports</span>
            </div>
        </div>
        <div class="tile bg-darkOrange">
            <div class="tile-content icon">
                <i class="icon-stats-2"></i>
            </div>
            <div class="tile-status">
                <span class="name">Dash Board</span>
            </div>
        </div>
        <div class="tile bg-darkCyan">
            <div class="tile-content icon">
                <i class="icon-help"></i>
            </div>
            <div class="tile-status">
                <span class="name">Help</span>
            </div>
        </div>

    </div>
</body>
</html>
