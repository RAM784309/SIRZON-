<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SIRZON Finance Management System</title>
<style>
/* COMBINED & UPDATED STYLES */
*{ box-sizing:border-box; margin:0; padding:0; font-family:Arial,sans-serif; }
body{ background:#eef7f0; color:#222; }

/* LOGIN */
.login-page{ min-height:100vh; display:flex; align-items:center; justify-content:center; padding:20px; background:linear-gradient(135deg,#198754,#0f5132); }
.login-box{ width:100%; max-width:400px; background:white; padding:30px; border-radius:20px; box-shadow:0 10px 30px rgba(0,0,0,.2); }
.logo{ text-align:center; font-size:34px; font-weight:bold; color:#198754; margin-bottom:5px; }
.subtitle{ text-align:center; color:#777; margin-bottom:25px; }
input,select{ width:100%; padding:13px; border:1px solid #ddd; border-radius:10px; margin:7px 0 12px; outline:none; }
button{ border:0; border-radius:10px; padding:13px 18px; cursor:pointer; }
.login-btn{ width:100%; background:#198754; color:white; font-size:16px; font-weight:bold; }
.register-link{ text-align:center; margin-top:18px; color:#198754; cursor:pointer; }

/* APP CONTAINER */
.app{ display:none; min-height:100vh; padding-bottom:75px; }

/* HEADER */
.header{ height:60px; background:#087a32; color:white; display:flex; align-items:center; padding:0 15px; position:sticky; top:0; z-index:1000; justify-content:space-between; }
.header-left{ display:flex; align-items:center; gap:8px; }
.menu-btn{ width:40px; height:40px; border:none; background:transparent; color:white; font-size:28px; cursor:pointer; display:flex; align-items:center; justify-content:center; }
.header-title{ margin-left:5px; font-size:23px; font-weight:bold; }
.header-right{ display:flex; align-items:center; }

/* NOTIFICATION */
.notif-bell{ position:relative; width:42px; height:42px; background:white; color:#198754; border-radius:50%; display:flex; align-items:center; justify-content:center; font-size:22px; cursor:pointer; box-shadow:0 2px 6px rgba(0,0,0,.15); }
.notif-badge{ position:absolute; top:-5px; right:-5px; min-width:20px; height:20px; padding:0 5px; background:#dc3545; color:white; border:none; border-radius:50%; display:none; align-items:center; justify-content:center; font-size:11px; font-weight:bold; line-height:20px; text-align:center; }

/* LEFT SIDEBAR */
.sidebar{ position:fixed; top:0; left:-280px; width:280px; height:100vh; background:white; box-shadow:3px 0 15px rgba(0,0,0,.25); z-index:2000; transition:left .3s ease; overflow-y:auto; }
.sidebar.open{ left:0; }
.sidebar-head{ height:60px; background:#087a32; color:white; display:flex; align-items:center; justify-content:space-between; padding:0 15px; }
.sidebar-head b{ font-size:22px; }
.close-btn{ border:none; background:transparent; color:white; font-size:30px; cursor:pointer; }

/* USER PROFILE IN SIDEBAR */
.user-box{ padding:20px; border-bottom:1px solid #ddd; background:#f0fff6; }
.user-name{ font-size:19px; font-weight:bold; color:#198754; }
.user-role{ margin-top:5px; color:#087a32; font-size:14px; }
.user-details{ margin-top:10px; font-size:13px; color:#555; }
.user-details p{ margin:4px 0; }

/* SIDEBAR NAV */
.nav{ padding:10px; }
.nav button{ width:100%; padding:14px 15px; margin-bottom:5px; border:none; background:white; text-align:left; border-radius:8px; font-size:15px; cursor:pointer; color:#222; }
.nav button:hover{ background:#eef7f0; }
.nav button.active{ background:#e1f3e6; color:#087a32; font-weight:bold; }

/* OVERLAY */
.overlay{ position:fixed; inset:0; background:rgba(0,0,0,.4); display:none; z-index:1500; }
.overlay.show{ display:block; }

/* MODAL */
.modal-overlay{ display:none; position:fixed; top:0; left:0; right:0; bottom:0; background:rgba(0,0,0,.5); z-index:2500; align-items:center; justify-content:center; padding:20px; }
.modal-box{ background:white; width:100%; max-width:380px; padding:20px; border-radius:15px; box-shadow:0 5px 20px rgba(0,0,0,.2); }
.modal-header{ display:flex; justify-content:space-between; align-items:center; margin-bottom:12px; }

/* PAGES */
.page{ display:none; padding:18px; max-width:1000px; margin:auto; }
.page.active{ display:block; }

/* PAGE HEADER WITH MONTH/YEAR BADGE */
.page-header-row { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; }
.page-title{ color:#087a32; font-size:24px; font-weight:bold; margin-bottom:0; }
.real-time-badge { background: #e1f3e6; color: #087a32; padding: 6px 12px; border-radius: 20px; font-size: 13px; font-weight: bold; border: 1px solid #c3e6cb; box-shadow: 0 1px 3px rgba(0,0,0,0.05); }

.welcome{ background:white; padding:20px; border-radius:15px; margin-bottom:15px; box-shadow:0 2px 8px rgba(0,0,0,.06); }

/* CARDS */
.cards{ display:grid; grid-template-columns:repeat(auto-fit,minmax(150px,1fr)); gap:12px; }
.card{ background:white; padding:18px; border-radius:15px; box-shadow:0 2px 8px rgba(0,0,0,.06); }
.card-title, .card h3{ color:#777; font-size:13px; }
.card-value, .card p{ font-size:22px; font-weight:bold; margin-top:8px; color:#198754; }
.section-title{ margin:20px 0 12px; color:#087a32; }

/* FORMS */
.form-box{ background:white; padding:18px; border-radius:15px; display:none; margin-top:12px; box-shadow:0 2px 8px rgba(0,0,0,.06); }
.form-box.active{ display:block; }
.form-group{ margin-bottom:15px; }
.form-group label{ display:block; font-weight:bold; margin-bottom:6px; }

/* TRANSACTION GRID */
.trans-grid{ display:grid; grid-template-columns:1fr 1fr; gap:12px; margin-top:10px; }
.trans-main-btn{ background:white; padding:18px; border-radius:12px; box-shadow:0 2px 8px rgba(0,0,0,.06); border:1px solid #e2e8f0; text-align:center; font-size:15px; font-weight:bold; color:#198754; cursor:pointer; transition:.2s; }
.trans-main-btn:hover{ background:#198754; color:white; }

.list{ margin-top:15px; }
.item, .list-item{ background:white; padding:15px; border-radius:12px; margin-bottom:10px; box-shadow:0 2px 8px rgba(0,0,0,.05); display:flex; justify-content:space-between; align-items:center; user-select:none; }

/* FIXED BOTTOM NAVIGATION BAR */
.bottom-nav{ position:fixed; bottom:0; left:0; right:0; height:68px; background:white; display:flex; justify-content:space-around; align-items:center; box-shadow:0 -2px 10px rgba(0,0,0,.12); z-index:1500; }
.nav-btn{ background:none; color:#777; font-size:11px; text-align:center; border:none; cursor:pointer; flex:1; padding:6px 0; display: flex; flex-direction: column; align-items: center; justify-content: center; }
.nav-btn.active{ color:#198754; font-weight:bold; }
.icon{ display:block; font-size:20px; margin-bottom:3px; line-height: 1; }

/* PASSWORD POPUP */
.password-popup{ position:fixed; top:0; left:0; right:0; bottom:0; background:rgba(0,0,0,.5); z-index:3000; display:none; align-items:center; justify-content:center; padding:20px; }
.password-popup.active{ display:flex; }
.password-box{ background:white; width:100%; max-width:380px; padding:20px; border-radius:15px; box-shadow:0 5px 25px rgba(0,0,0,.25); }
.password-box h3{ color:#198754; margin-bottom:15px; }
.password-actions{ display:flex; gap:10px; margin-top:5px; }
.password-actions button{ flex:1; }
.cancel-password{ background:#6c757d; color:white; }
.change-password-btn{ background:#198754; color:white; }

.empty{ background:white; padding:20px; text-align:center; border-radius:12px; color:#777; }

@media(max-width:500px){
  .cards{ grid-template-columns:1fr 1fr; }
}
</style>
</head>
<body>

<!-- LOGIN PAGE -->
<div id="loginPage" class="login-page">
  <div class="login-box">
    <div class="logo">SIRZON</div>
    <div class="subtitle"> Finance Management System </div>
    <div id="loginForm">
      <label>Mobile / Username</label>
      <input id="loginUser" type="text" placeholder="Enter username">
      <label>Password</label>
      <input id="loginPass" type="password" placeholder="Enter password">
      <button class="login-btn" onclick="login()"> LOGIN </button>
      <div class="register-link" onclick="showRegister()"> Create New Account </div>
    </div>
    <div id="registerForm" style="display:none">
      <label>Full Name</label>
      <input id="regName" type="text" placeholder="Enter name">
      <label>Username</label>
      <input id="regUser" type="text" placeholder="Create username">
      <label>Password</label>
      <input id="regPass" type="password" placeholder="Create password">
      <button class="login-btn" onclick="register()"> REGISTER </button>
      <div class="register-link" onclick="showLogin()"> Already have an account? Login </div>
    </div>
  </div>
</div>

<!-- MAIN APP -->
<div id="app" class="app">

  <!-- OVERLAY -->
  <div class="overlay" id="overlay" onclick="closeMenu()"></div>

  <!-- SIDEBAR MENU -->
  <div class="sidebar" id="sidebar">
    <div class="sidebar-head">
      <b>SIRZON</b>
      <button class="close-btn" onclick="closeMenu()">×</button>
    </div>

    <!-- USER PROFILE -->
    <div class="user-box">
      <div class="user-name" id="sideMemberName">Sriram Soren</div>
      <div class="user-role" id="sideMemberRole">Member</div>
      <div class="user-details">
        <p><b>Branch:</b> <span id="sideMemberBranch">N/A</span></p>
        <p><b>Name:</b> <span id="sideMemberProfileName">Sriram Soren</span></p>
        <p><b>Role:</b> <span id="sideMemberProfileRole">Member</span></p>
        <p><b>Join date:</b> <span id="sideMemberJoinDate">06/09/2026</span></p>
        <p><b>Usercode:</b> <span id="sideMemberCode">MB0001</span></p>
        <p><b>Password:</b> <span id="sideMemberPasswordText">1234</span> <button onclick="togglePasswordVisibility()" style="border:none;background:none;color:#198754;cursor:pointer;font-size:12px;text-decoration:underline;margin-left:5px;" id="togglePassBtn">Show</button></p>
      </div>
    </div>

    <!-- MENU LINKS -->
    <div class="nav" id="navMenu">
      <button onclick="openChangePassword()" style="background:#f8f9fa;">
        🔐 &nbsp; Change Password
      </button>
      <button onclick="logout()" style="color:red;">
        🚪 &nbsp; Logout
      </button>
    </div>
  </div>

  <!-- HEADER -->
  <div class="header">
    <div class="header-left">
      <button class="menu-btn" onclick="openMenu()"> ☰ </button>
      <div class="header-title">SIRZON</div>
    </div>
    <div class="header-right">
      <div class="notif-bell" onclick="toggleNotifModal(true)">
        🔔 <span class="notif-badge" id="notifBadge">0</span>
      </div>
    </div>
  </div>
<!-- MEMBER HOME -->
<div class="page" id="memberHomePage">

  <div class="page-header-row">
    <div class="page-title">Home</div>
    <div class="real-time-badge" id="memberHomeRealTimeBadge">September 2026</div>
  </div>

  <div class="welcome" style="text-align:center;">
    <div class="card-title">Total Balance</div>
    <div class="card-value" id="memberHomeTotalBalance" style="font-size:28px;">
      ₹0
    </div>
  </div>
<!-- MANAGER LOAN SETTINGS -->
<div id="managerLoanSettings"
     class="card"
     style="display:none;margin-top:15px;">

  <h3 style="color:#198754;">
    ⚙️ Loan Interest Settings
  </h3>

  <p style="font-size:13px;color:#666;margin:8px 0 15px;">
    Set interest rate for your branch.
    Members will see this rate automatically.
  </p>

  <label>Weekly Loan Interest (%)</label>

  <input id="managerWeeklyRate"
         type="number"
         min="0"
         step="0.01"
         placeholder="Weekly %">

  <label>Monthly Loan Interest (%)</label>

  <input id="managerMonthlyRate"
         type="number"
         min="0"
         step="0.01"
         placeholder="Monthly %">

  <button class="login-btn"
          onclick="saveManagerLoanRates()">
    SAVE LOAN RATES
  </button>

</div>
  <h3 class="section-title">Quick Transaction</h3>

  <div class="trans-grid">

    <button class="trans-main-btn"
            onclick="toggleMemberForm('memberSavingForm')">
      💰 Saving
    </button>

    <button class="trans-main-btn"
            onclick="toggleMemberForm('memberEmiForm')">
      📥 EMI Pay
    </button>

  </div>

  <!-- MEMBER SAVING -->
  <div class="form-box" id="memberSavingForm">

    <h4>💰 Saving</h4>

    <label>Amount</label>
    <input id="memberSavingAmount"
           type="number"
           min="1"
           placeholder="Enter saving amount">

    <button class="login-btn"
            onclick="memberAddSaving()">
      SUBMIT SAVING
    </button>

  </div>

  <!-- MEMBER EMI -->
  <div class="form-box" id="memberEmiForm">

    <h4>📥 EMI Pay</h4>

    <div id="memberEmiLoanInfo"
         style="background:#f8f9fa;
                padding:12px;
                border-radius:10px;
                margin-bottom:12px;
                font-size:13px;">
      Loading loan...
    </div>

    <label>EMI Amount</label>

    <input id="memberEmiAmount"
           type="number"
           min="1"
           placeholder="Enter EMI amount">

    <button class="login-btn"
            onclick="memberPayEmi()">
      PAY EMI
    </button>

  </div>

  <!-- SEARCH -->
  <div style="margin-top:15px;">

    <input type="text"
           id="memberTransactionSearch"
           placeholder="🔍 Search transactions..."
           oninput="renderMemberTransactions()"
           style="margin:0 0 5px 0;">

  </div>

  <!-- TRANSACTIONS -->
  <div class="list" id="memberTransactionList"></div>

</div>

  <!-- HOME -->
  <div class="page active" id="homePage">
    <div class="page-header-row">
      <div class="page-title">Home</div>
      <div class="real-time-badge" id="homeRealTimeBadge">September 2026</div>
    </div>

    <div class="welcome" style="text-align:center;">
      <div class="card-title"> Total Balance </div>
      <div class="card-value" id="totalBalance" style="font-size:28px;"> ₹0 </div>
    </div>

    <div class="cards">
      <div class="card">
        <div class="card-title"> Savings Amount </div>
        <div class="card-value" id="totalSavings"> ₹0 </div>
      </div>
      <div class="card">
        <div class="card-title"> Available Savings </div>
        <div class="card-value" id="availableSavings"> ₹0 </div>
      </div>
      <div class="card">
        <div class="card-title"> Earnings Balance </div>
        <div class="card-value" id="totalRemainingBalance"> ₹0 </div>
      </div>
      <div class="card">
        <div class="card-title"> Active Loan </div>
        <div class="card-value" id="totalLoan"> ₹0 </div>
      </div>
    </div>

    <h3 class="section-title"> Quick Transaction </h3>
    <div class="trans-grid">
      <button class="trans-main-btn" onclick="toggleForm('formSavings')"> 💰 Savings </button>
      <button class="trans-main-btn" onclick="toggleForm('formLoan')"> 💳 New Loan </button>
      <button class="trans-main-btn" onclick="toggleForm('formEmi')"> 📥 EMI Collect </button>
      <button class="trans-main-btn" onclick="toggleForm('formOthers')"> 🔄 Others IN/OUT </button>
    </div>

    <!-- SAVINGS FORM -->
    <div class="form-box" id="formSavings">
      <h4>Add Savings</h4>
      <label>Select Branch</label>
      <input type="text" id="searchSavBranch" placeholder="Search branch..." oninput="filterDropdown('searchSavBranch','savBranch')">
      <select id="savBranch" onchange="filterMembersByBranch('savBranch','savMember')">
        <option value=""> Select Branch First </option>
      </select>
      <label>Select Member</label>
      <input type="text" id="searchSavMember" placeholder="Search member..." oninput="filterDropdown('searchSavMember','savMember')">
      <select id="savMember">
        <option value=""> Select Branch First </option>
      </select>
      <label>Amount</label>
      <input id="amtSavings" type="number" placeholder="Enter amount">
      <button class="login-btn" onclick="addSavingsTrans()"> Submit Saving </button>
    </div>

    <!-- NEW LOAN FORM -->
    <div class="form-box" id="formLoan">
      <h4>New Loan Entry</h4>
      <label>Select Branch</label>
      <input type="text" id="searchLoanBranch" placeholder="Search branch..." oninput="filterDropdown('searchLoanBranch','loanBranch')">
      <select id="loanBranch" onchange="filterMembersByBranch('loanBranch','loanMemberSel')">
        <option value=""> Select Branch First </option>
      </select>
      <label>Select Member</label>
      <input type="text" id="searchLoanMember" placeholder="Search member..." oninput="filterDropdown('searchLoanMember','loanMemberSel')">
      <select id="loanMemberSel">
        <option value=""> Select Branch First </option>
      </select>
      <label>Loan Amount</label>
      <input id="amtLoan" type="number" placeholder="Enter amount" oninput="calculateLoanEmiPreview()">
      <label>Interest Rate (%)</label>
      <input id="loanInterestRate" type="number" placeholder="Enter interest rate %" value="10" oninput="calculateLoanEmiPreview()">
      <label>Duration Type</label>
      <select id="loanDurationType" onchange="calculateLoanEmiPreview()">
        <option value="Weeks">Weeks</option>
        <option value="Months">Months</option>
      </select>
      <label>Duration Value</label>
      <input id="loanDurationVal" type="number" placeholder="Enter duration value" oninput="calculateLoanEmiPreview()">
      <p style="margin:10px 0;font-weight:bold;color:#198754;" id="loanEmiPreviewBox"> Total Payable: ₹0 | Installment: ₹0 </p>
      <button class="login-btn" onclick="addNewLoanTrans()"> Submit Loan </button>
    </div>

    <!-- EMI FORM -->
    <div class="form-box" id="formEmi">
      <h4>Collect EMI</h4>
      <label>Select Branch</label>
      <input type="text" id="searchEmiBranch" placeholder="Search branch..." oninput="filterDropdown('searchEmiBranch','emiBranch')">
      <select id="emiBranch" onchange="filterMembersByBranch('emiBranch','emiMember')">
        <option value=""> Select Branch First </option>
      </select>
      <label>Select Member</label>
      <input type="text" id="searchEmiMember" placeholder="Search member..." oninput="filterDropdown('searchEmiMember','emiMember')">
      <select id="emiMember" onchange="loadMemberActiveLoan()">
        <option value=""> Select Branch First </option>
      </select>
      <div id="memberLoanInfo" style="background:#f8f9fa;padding:10px;border-radius:8px;margin-bottom:10px;font-size:13px;color:#555;display:none;"></div>
      <label>Principal Amount</label>
      <input id="emiPrincipal" type="number" placeholder="Principal amount" oninput="calculateEmiTotal()">
      <label>Interest Amount</label>
      <input id="emiInterest" type="number" placeholder="Interest amount" oninput="calculateEmiTotal()">
      <p style="margin-bottom:10px;font-weight:bold;color:#198754;"> Total Amount: <span id="emiTotalDisplay"> ₹0 </span> </p>
      <button class="login-btn" onclick="addEmiTrans()"> Submit EMI </button>
    </div>

    <!-- OTHERS FORM -->
    <div class="form-box" id="formOthers">
      <h4>Others IN/OUT</h4>
      <select id="typeOthers">
        <option value="Other IN"> IN (+) </option>
        <option value="Other OUT"> OUT (-) </option>
      </select>
      <input id="amtOthers" type="number" placeholder="Enter amount">
      <input id="descOthers" type="text" placeholder="Enter description/purpose">
      <button class="login-btn" onclick="addQuickTransOthers()"> Submit Others </button>
    </div>

    <!-- SEARCH TRANSACTIONS -->
    <div style="margin-top:15px;">
      <input type="text" id="searchTransactionInput" placeholder="🔍 Search transactions by member, code, type..." oninput="renderTransactions()" style="margin:0 0 5px 0;">
    </div>
    <div class="list" id="transactionList"></div>
  </div>

  <!-- DISTRIBUTE -->
  <div class="page" id="distributePage">
    <div class="page-header-row">
      <div class="page-title">💸 Distribute</div>
      <div class="real-time-badge" id="distributeRealTimeBadge">September 2026</div>
    </div>
    <div class="form-box active" style="margin-top:15px">
      <!-- Available Earning Balance Card -->
      <div style="margin-bottom:15px; padding:15px; background:#f0fff6; border-radius:10px; border:1px solid #d5eadc; text-align:center;">
        <div style="font-size:14px;color:#555;"> Total Available Earnings Pool </div>
        <div id="distributionAvailableBalance" style="font-size:26px;font-weight:bold;margin-top:5px;color:#198754;"> ₹0 </div>
      </div>

      <div id="adminBranchSelectContainer" style="display:none;">
        <label>Select Branch</label>
        <input type="text" id="searchDistributeBranch" placeholder="🔍 Search branch name or code..." oninput="filterDropdown('searchDistributeBranch','distributeBranchSelect')">
        <select id="distributeBranchSelect" onchange="onDistributeBranchChange()">
          <option value="">Select Branch</option>
        </select>
      </div>

      <label>Select Member</label>
      <input type="text" id="searchDistributeMember" placeholder="🔍 Search member..." oninput="filterDropdown('searchDistributeMember','distributeMember')">
      <select id="distributeMember" onchange="calculateSelectedMemberDistribution()">
        <option value=""> Select Member </option>
      </select>

      <!-- Member Share & Calculation Info Box -->
      <div id="distributionShareInfo" style="display:none; margin-top:12px; padding:15px; background:#f8f9fa; border-radius:10px; border:1px solid #e2e8f0;"></div>

      <label style="margin-top:12px;">Distribution Amount (Auto-Calculated)</label>
      <input id="distributeAmount" type="number" readonly placeholder="Select member to calculate amount" style="background:#eef7f0; font-weight:bold; color:#198754;">

      <label>Description / Note</label>
      <input id="distributeDescription" type="text" placeholder="Enter purpose / description (e.g. Monthly Profit Share)">

      <button class="login-btn" style="margin-top:10px;" onclick="addDistribute()"> 💸 APPLY & DISTRIBUTE </button>
    </div>

    <div style="margin-top:15px;">
      <input type="text" id="searchDistributeInput" placeholder="🔍 Search distribution history by member, code, or branch..." oninput="renderDistributions()">
    </div>
    <div class="list" id="distributeList"></div>
  </div>

  <!-- BRANCH -->
  <div class="page" id="branchPage">
    <div class="page-header-row">
      <div class="page-title">🏢 Branch</div>
      <div class="real-time-badge" id="branchRealTimeBadge">September 2026</div>
    </div>
    <div class="form-box active" style="margin-top:15px">
      <div class="form-group"><label>Branch Name</label><input id="branchName" type="text" placeholder="Enter branch name"></div>
      <div class="form-group"><label>Manager Name</label><input id="branchManager" type="text" placeholder="Enter manager name"></div>
      <div class="form-group"><label>Manager Password</label><input id="branchManagerPassword" type="password" placeholder="Create manager password"></div>
      <div class="form-group"><label>Mobile Number</label><input id="branchMobile" type="tel" placeholder="Enter mobile number"></div>
      <div class="form-group"><label>Branch Address</label><input id="branchAddress" type="text" placeholder="Enter branch address"></div>
      <button class="login-btn" onclick="addBranch()"> ADD BRANCH </button>
    </div>
    <div style="margin-top:15px;">
      <input type="text" id="searchBranchInput" placeholder="🔍 Search branch name or code..." oninput="renderBranches()">
    </div>
    <div class="list" id="branchList"></div>
  </div>

  <!-- TEAM -->
  <div class="page" id="teamPage">
    <div class="page-header-row">
      <div class="page-title">👥 Team</div>
      <div class="real-time-badge" id="teamRealTimeBadge">September 2026</div>
    </div>
    <div class="form-box active" style="margin-top:15px" id="addMemberFormBox">
      <div class="form-group"><label>Search Branch</label><input id="searchMemberBranch" type="text" placeholder="🔍 Search branch name or code..." oninput="filterDropdown('searchMemberBranch','memberBranch')"></div>
      <div class="form-group"><label>Select Branch</label><select id="memberBranch"><option value=""> Select Branch </option></select></div>
      <div class="form-group"><label>Member Name</label><input id="memberName" type="text" placeholder="Enter member name"></div>
      <div class="form-group"><label>Mobile Number</label><input id="memberMobile" type="tel" placeholder="Enter mobile number"></div>
      <div class="form-group"><label>Address</label><input id="memberAddress" type="text" placeholder="Enter address"></div>
      <div class="form-group"><label>Member Password</label><input id="memberPassword" type="password" placeholder="Create member password"></div>
      <button class="login-btn" onclick="addMember()"> ADD MEMBER </button>
    </div>
    <div style="margin-top:15px;">
      <input type="text" id="searchMemberInput" placeholder="🔍 Search member name, branch name or code..." oninput="renderMembers()">
    </div>
    <div class="list" id="memberList"></div>
  </div>

  <!-- MEMBER LOAN -->
<div class="page" id="loanPageMember">

  <div class="page-header-row">
    <div class="page-title">💳 Loan</div>
    <div class="real-time-badge" id="loanRealTimeBadge">
      September 2026
    </div>
  </div>

  <div class="cards">

    <div class="card">
      <div class="card-title">Active Loan</div>
      <div class="card-value" id="memberActiveLoanVal">
        ₹0
      </div>
    </div>

  </div>

  <div class="form-box active" style="margin-top:15px;">

    <h4>Apply Loan</h4>

    <label>Select Amount</label>

    <input id="memberLoanAmount"
           type="number"
           min="1"
           placeholder="Enter loan amount"
           oninput="calculateMemberLoan()">

    <label>Choose Week or Month</label>

    <select id="memberLoanType"
            onchange="updateMemberLoanRate();calculateMemberLoan();">

      <option value="Weeks">Week</option>
      <option value="Months">Month</option>

    </select>

    <label>Enter Number</label>

    <input id="memberLoanNumber"
           type="number"
           min="1"
           placeholder="Enter number"
           oninput="calculateMemberLoan()">

    <!-- AUTOMATIC MANAGER RATE -->
    <div style="
      background:#f0fff6;
      border:1px solid #c3e6cb;
      padding:14px;
      border-radius:10px;
      margin:10px 0;
      text-align:center;
    ">

      <div style="font-size:13px;color:#666;">
        Manager Set Interest Rate
      </div>

      <div id="memberLoanRate"
           style="
           font-size:23px;
           font-weight:bold;
           color:#198754;
           margin-top:5px;">
        0%
      </div>

    </div>

    <div id="memberLoanCalculation"
         style="
         background:#f8f9fa;
         padding:12px;
         border-radius:10px;
         margin-bottom:12px;
         font-size:14px;">
      Total Payable: ₹0<br>
      Installment: ₹0
    </div>

    <button class="login-btn"
            onclick="memberApplyLoan()">
      APPLY LOAN
    </button>

  </div>

  <!-- SEARCH -->
  <div style="margin-top:15px;">

    <input type="text"
           id="memberLoanSearch"
           placeholder="🔍 Search loan history..."
           oninput="renderMemberLoanHistory()">

  </div>

  <!-- HISTORY -->
  <div class="list" id="memberLoanList"></div>

</div>

<!-- MEMBER EARNING -->
<div class="page" id="earningPageMember">

  <div class="page-header-row">

    <div class="page-title">💸 Earning</div>

    <div class="real-time-badge" id="earningRealTimeBadge">
      September 2026
    </div>

  </div>

  <div class="cards">

    <div class="card">
      <div class="card-title">
        Self Earning
      </div>

      <div class="card-value"
           id="memberSelfEarning">
        ₹0
      </div>
    </div>

    <div class="card">
      <div class="card-title">
        Earning Withdrawal
      </div>

      <div class="card-value"
           id="memberEarningWithdrawal">
        ₹0
      </div>
    </div>

    <div class="card">
      <div class="card-title">
        Available Earning
      </div>

      <div class="card-value"
           id="memberAvailableEarning">
        ₹0
      </div>
    </div>

  </div>

  <div class="form-box active"
       style="margin-top:15px;">

    <h4>Request Earning Withdrawal</h4>

    <label>Amount</label>

    <input id="earningRequestAmount"
           type="number"
           min="1"
           placeholder="Enter withdrawal amount">

    <button class="login-btn"
            onclick="requestEarningWithdrawal()">
      REQUEST
    </button>

  </div>

  <!-- SEARCH -->
  <div style="margin-top:15px;">

    <input type="text"
           id="memberEarningSearch"
           placeholder="🔍 Search earning history..."
           oninput="renderMemberEarningHistory()">

  </div>

  <!-- HISTORY -->
  <div class="list"
       id="memberEarningsList"></div>

</div>

  <!-- ACCOUNT -->
  <!-- MEMBER ACCOUNT SUMMARY -->
<div id="memberAccountSummary" style="display:none;">

  <div class="cards">

    <div class="card">
      <div class="card-title">
        Total Savings
      </div>

      <div class="card-value"
           id="accountMemberTotalSavings">
        ₹0
      </div>
    </div>

    <div class="card">
      <div class="card-title">
        Current Savings
      </div>

      <div class="card-value"
           id="accountMemberCurrentSavings">
        ₹0
      </div>
    </div>

    <div class="card">
      <div class="card-title">
        Earning
      </div>

      <div class="card-value"
           id="accountMemberEarning">
        ₹0
      </div>
    </div>

    <div class="card">
      <div class="card-title">
        Total Balance
      </div>

      <div class="card-value"
           id="accountMemberTotalBalance">
        ₹0
      </div>
    </div>

  </div>

  <div class="card"
       style="margin-top:15px;">

    <h3 style="color:#198754;">
      Balance Formula
    </h3>

    <p style="margin-top:10px;font-size:14px;">
      Earning =
      Self Earning − Earning Withdrawal
    </p>

    <p style="margin-top:8px;font-size:14px;">
      Total Balance =
      Current Savings + Earning
    </p>

  </div>

</div>
  <div class="page" id="accountPage">
    <div class="page-header-row">
      <div class="page-title">Account</div>
      <div class="real-time-badge" id="accountRealTimeBadge">September 2026</div>
    </div>
    <div class="card" style="margin-top:15px">
      <h3 id="accountName" style="font-size:20px; color:#198754;"> User </h3>
      <p style="margin-top:8px"> Username: <span id="accountUser"></span> </p>
      <p style="margin-top:8px"> Role: <b id="accountRole"></b> </p>
      <p style="margin-top:8px"> Total Branches: <b id="accountBranches">0</b> </p>
      <p style="margin-top:8px"> Total Members: <b id="accountMembers">0</b> </p>
    </div>

    <!-- BACKUP -->
    <div class="card" style="margin-top:15px;">
      <h3 style="color:#198754;margin-bottom:10px;font-size:16px;"> 💾 Data Backup & Restore </h3>
      <p style="font-size:13px;color:#666;margin-bottom:12px;"> Download a backup file of your entire database or restore from a previous backup file. </p>
      <div style="display:flex;gap:10px;">
        <button class="login-btn" style="background:#0d6efd;font-size:14px;padding:10px;" onclick="exportBackupData()"> Backup JSON </button>
        <button class="login-btn" style="background:#6c757d;font-size:14px;padding:10px;" onclick="document.getElementById('importFile').click()"> Restore JSON </button>
        <input type="file" id="importFile" style="display:none" accept=".json" onchange="importBackupData(event)">
      </div>
    </div>

    <div style="margin-top:15px;text-align:center;">
      <button class="login-btn" style="background:#dc3545;width:auto;padding:10px 25px;font-size:14px;" onclick="logout()"> LOGOUT </button>
    </div>
  </div>

  <!-- FIXED BOTTOM NAVIGATION BAR -->
  <div class="bottom-nav" id="bottomNav">

  <button class="nav-btn active"
          onclick="openPage('homePage', this)"
          id="navHomeBtn">
    <span class="icon">🏠</span>Home
  </button>

  <button class="nav-btn"
          onclick="openPage('teamPage', this)"
          id="navTeamBtn">
    <span class="icon">👥</span>Team
  </button>

  <button class="nav-btn"
          onclick="openPage('branchPage', this)"
          id="navBranchBtn">
    <span class="icon">🏢</span>Branch
  </button>

  <button class="nav-btn"
          onclick="openPage('distributePage', this)"
          id="navDistributeBtn">
    <span class="icon">💰</span>Distribute
  </button>

  <button class="nav-btn"
          onclick="openPage('accountPage', this)"
          id="navAccountBtn">
    <span class="icon">👤</span>Account
  </button>

</div>

<!-- NOTIFICATION MODAL -->
<div class="modal-overlay" id="notifModal">
  <div class="modal-box">
    <div class="modal-header">
      <h3 style="color:#198754;"> 🔔 Active Dues & Reminders </h3>
      <button style="background:none;font-size:18px;padding:0;cursor:pointer;" onclick="toggleNotifModal(false)"> ✕ </button>
    </div>
    <div id="notifListContent" style="font-size:14px;max-height:280px;overflow-y:auto;color:#555;"> No upcoming reminders. </div>
  </div>
</div>

<!-- CHANGE PASSWORD MODAL -->
<div class="password-popup" id="passwordPopup">
  <div class="password-box">
    <h3>🔐 Change Password</h3>
    <label>Current Password</label>
    <input id="currentPassword" type="password" placeholder="Enter current password">
    <label>New Password</label>
    <input id="newPassword" type="password" placeholder="Enter new password">
    <label>Confirm Password</label>
    <input id="confirmPassword" type="password" placeholder="Confirm new password">
    <div class="password-actions">
      <button class="cancel-password" onclick="closeChangePassword()"> Cancel </button>
      <button class="change-password-btn" onclick="changeMemberPassword()"> Change </button>
    </div>
  </div>
</div>

<script>
/* ===================================================== DATABASE ===================================================== */
var defaultDB = {
  users:[],
  branches:[],
  members:[],
  transactions:[],
  loans:[],
  loanRequests:[],
  earningRequests:[]
};
var db;
try{
  db = JSON.parse( localStorage.getItem("sirzon_db") );
}catch(error){
  db = null;
}
if(!db || typeof db !== "object"){ db = defaultDB; }
if(!Array.isArray(db.users)){ db.users = []; }
if(!Array.isArray(db.branches)){ db.branches = []; }
if(!Array.isArray(db.members)){ db.members = []; }
if(!Array.isArray(db.transactions)){ db.transactions = []; }
if(!Array.isArray(db.loans)){ db.loans = []; }
if(!Array.isArray(db.loanRequests)){ db.loanRequests = []; }
if(!Array.isArray(db.earningRequests)){ db.earningRequests = []; }

function saveDB(){
  localStorage.setItem( "sirzon_db", JSON.stringify(db) );
}

function fourDigit(num){
  return ("0000" + num).slice(-4);
}

/* ===================================================== REAL-TIME CURRENT MONTH & YEAR ===================================================== */
function updateRealTimeBadges() {
  var now = new Date();
  var options = { month: 'long', year: 'numeric' };
  var currentMonthYear = now.toLocaleDateString('en-US', options); 
  var badgeIds = [
    "homeRealTimeBadge",
    "distributeRealTimeBadge",
    "branchRealTimeBadge",
    "teamRealTimeBadge",
    "loanRealTimeBadge",
    "earningRealTimeBadge",
    "accountRealTimeBadge"
  ];
  badgeIds.forEach(function(id){
    var el = document.getElementById(id);
    if(el) { el.innerText = currentMonthYear; }
  });
}

/* ===================================================== BACKUP ===================================================== */
function exportBackupData(){
  var dataStr = "data:text/json;charset=utf-8," + encodeURIComponent( JSON.stringify(db,null,2) );
  var downloadAnchor = document.createElement("a");
  downloadAnchor.setAttribute( "href", dataStr );
  downloadAnchor.setAttribute( "download", "sirzon_finance_backup_" + new Date().toISOString().slice(0,10) + ".json" );
  document.body.appendChild( downloadAnchor );
  downloadAnchor.click();
  if(downloadAnchor.parentNode){
    downloadAnchor.parentNode.removeChild( downloadAnchor );
  }
}

function importBackupData(event){
  var file = event.target.files[0];
  if(!file) return;
  var reader = new FileReader();
  reader.onload = function(e){
    try{
      var parsedData = JSON.parse( e.target.result );
      if( parsedData && Array.isArray(parsedData.users) && Array.isArray(parsedData.branches) && Array.isArray(parsedData.members) ){
        if( confirm( "Are you sure you want to restore data?\n\nThis will overwrite existing local data." ) ){
          db = parsedData;
          if(!Array.isArray(db.transactions)){ db.transactions = []; }
          if(!Array.isArray(db.loans)){ db.loans = []; }
          saveDB();
          refreshAll();
          alert( "Database restored successfully!" );
        }
      }else{
        alert( "Invalid backup file format." );
      }
    }catch(err){
      alert( "Error reading backup file." );
    }
  };
  reader.readAsText(file);
  event.target.value = "";
}

/* ===================================================== REGISTER / LOGIN ===================================================== */
function register(){
  var name = document.getElementById("regName").value.trim();
  var username = document.getElementById("regUser").value.trim();
  var password = document.getElementById("regPass").value;
  if(!name || !username || !password){
    alert( "Please fill all fields" );
    return;
  }
  var exists = db.users.some( function(u){ return u.username === username; } );
  if(exists){
    alert( "Username already exists" );
    return;
  }
  db.users.push({
    id:Date.now(),
    name:name,
    username:username,
    password:password,
    role:"PENDING",
    joinDate: new Date().toLocaleDateString()
  });
  saveDB();
  alert( "Account created successfully.\nRole will be assigned by Admin." );
  document.getElementById("regName").value = "";
  document.getElementById("regUser").value = "";
  document.getElementById("regPass").value = "";
  showLogin();
}

function login(){
  var username = document.getElementById("loginUser").value.trim();
  var password = document.getElementById("loginPass").value;
  if(!username || !password){
    alert( "Please enter code and password" );
    return;
  }
  var user = db.users.find( function(u){
    return ( u.username === username && u.password === password );
  } );
  if( username === "admin" && password === "1234" ){
    user = { id:"ADMIN", name:"Administrator", username:"admin", password:"1234", role:"AD", joinDate:"01/01/2026", code:"AD0001" };
  }
  if(!user){
    alert( "Invalid code or password" );
    return;
  }
  if(user.role === "PENDING"){
    alert( "This account has no role yet.\nPlease contact Admin." );
    return;
  }
  if( user.role !== "AD" && user.role !== "BR" && user.role !== "MB" ){
    alert( "Invalid user role" );
    return;
  }
  localStorage.setItem( "sirzon_current_user", JSON.stringify(user) );
  currentUser = user;
  showApp(user);
}

function showApp(user){

  document.getElementById("loginPage").style.display = "none";
  document.getElementById("app").style.display = "block";

  document.getElementById("accountName").innerText =
    user.name || "User";

  document.getElementById("accountUser").innerText =
    user.username || "";

  document.getElementById("accountRole").innerText =
    user.role === "AD"
      ? "Admin"
      : (user.role === "BR" ? "Manager" : "Member");

  applyRoleUIRestrictions(user);

  if(user.role === "MB"){

    openPage("memberHomePage");

  }else{

    openPage("homePage");

  }

  refreshAll();
}

function applyRoleUIRestrictions(user){

  var bottomNav = document.getElementById("bottomNav");

  var homeBtn = document.getElementById("navHomeBtn");
  var teamBtn = document.getElementById("navTeamBtn");
  var branchBtn = document.getElementById("navBranchBtn");
  var distributeBtn = document.getElementById("navDistributeBtn");
  var accountBtn = document.getElementById("navAccountBtn");

  if(user.role === "MB"){

    /* MEMBER NAVIGATION */

    homeBtn.style.display = "flex";
    homeBtn.innerHTML =
      '<span class="icon">🏠</span>Home';
    homeBtn.setAttribute(
      "onclick",
      "openPage('memberHomePage', this)"
    );

    teamBtn.style.display = "flex";
    teamBtn.innerHTML =
      '<span class="icon">💳</span>Loan';
    teamBtn.setAttribute(
      "onclick",
      "openPage('loanPageMember', this)"
    );

    branchBtn.style.display = "flex";
    branchBtn.innerHTML =
      '<span class="icon">💸</span>Earning';
    branchBtn.setAttribute(
      "onclick",
      "openPage('earningPageMember', this)"
    );

    distributeBtn.style.display = "none";

    accountBtn.style.display = "flex";

    accountBtn.innerHTML =
      '<span class="icon">👤</span>Account';

    accountBtn.setAttribute(
      "onclick",
      "openPage('accountPage', this)"
    );
loadManagerLoanSettings();

    /* MEMBER ACCOUNT */

    var memberSummary =
      document.getElementById("memberAccountSummary");

    if(memberSummary){
      memberSummary.style.display = "block";
    }

  }

  else if(user.role === "BR"){

    branchBtn.style.display = "none";
    teamBtn.style.display = "flex";
    distributeBtn.style.display = "flex";
    accountBtn.style.display = "flex";

  }

  else{

    teamBtn.style.display = "flex";
    branchBtn.style.display = "flex";
    distributeBtn.style.display = "flex";
    accountBtn.style.display = "flex";

  }
}

/* ===================================================== SIDEBAR MENU ===================================================== */
function openMenu(){
  document.getElementById("sidebar").classList.add("open");
  document.getElementById("overlay").classList.add("show");
  loadMemberSideProfile();
}

function closeMenu(){
  document.getElementById("sidebar").classList.remove("open");
  document.getElementById("overlay").classList.remove("show");
}

function loadMemberSideProfile(){
  if(!currentUser){ return; }
  var roleText = currentUser.role === "AD" ? "Admin" : (currentUser.role === "BR" ? "Manager" : "Member");
  document.getElementById("sideMemberName").innerText = currentUser.name || "User";
  document.getElementById("sideMemberRole").innerText = roleText;
  document.getElementById("sideMemberBranch").innerText = currentUser.branch || "N/A";
  document.getElementById("sideMemberProfileName").innerText = currentUser.name || "User";
  document.getElementById("sideMemberProfileRole").innerText = roleText;
  document.getElementById("sideMemberJoinDate").innerText = currentUser.joinDate || "06/09/2026";
  document.getElementById("sideMemberCode").innerText = currentUser.code || currentUser.memberId || currentUser.username || "MB0001";
  document.getElementById("sideMemberPasswordText").innerText = "••••";
  document.getElementById("sideMemberPasswordText").setAttribute("data-real", currentUser.password || "1234");
  document.getElementById("togglePassBtn").innerText = "Show";
}

function togglePasswordVisibility(){
  var passSpan = document.getElementById("sideMemberPasswordText");
  var btn = document.getElementById("togglePassBtn");
  var realPass = passSpan.getAttribute("data-real");
  if(passSpan.innerText === "••••"){
    passSpan.innerText = realPass;
    btn.innerText = "Hide";
  } else {
    passSpan.innerText = "••••";
    btn.innerText = "Show";
  }
}

function openChangePassword(){
  closeMenu();
  document.getElementById("passwordPopup").classList.add("active");
  document.getElementById("currentPassword").value = "";
  document.getElementById("newPassword").value = "";
  document.getElementById("confirmPassword").value = "";
}

function closeChangePassword(){
  document.getElementById("passwordPopup").classList.remove("active");
}

function changeMemberPassword(){
  if(!currentUser){
    alert( "User session not found." );
    return;
  }
  var current = document.getElementById("currentPassword").value;
  var newPass = document.getElementById("newPassword").value;
  var confirmPass = document.getElementById("confirmPassword").value;
  if(!current || !newPass || !confirmPass){
    alert( "Please fill all password fields." );
    return;
  }
  if(current !== currentUser.password){
    alert( "Current password is incorrect." );
    return;
  }
  if(newPass.length < 4){
    alert( "New password must be at least 4 characters." );
    return;
  }
  if(newPass !== confirmPass){
    alert( "New password and confirm password do not match." );
    return;
  }
  var userIndex = db.users.findIndex( function(u){
    return ( u.id === currentUser.id || u.code === currentUser.code || u.username === currentUser.username );
  } );
  if(userIndex !== -1){
    db.users[userIndex].password = newPass;
  }
  currentUser.password = newPass;
  localStorage.setItem( "sirzon_current_user", JSON.stringify(currentUser) );
  saveDB();
  alert( "Password changed successfully." );
  closeChangePassword();
}

function logout(){
  if(confirm("Are you sure you want to logout?")){
    localStorage.removeItem("sirzon_current_user");
    location.reload();
  }
}

function showRegister(){
  document.getElementById("loginForm").style.display = "none";
  document.getElementById("registerForm").style.display = "block";
}

function showLogin(){
  document.getElementById("loginForm").style.display = "block";
  document.getElementById("registerForm").style.display = "none";
}
function loadManagerLoanSettings(){

  if(!currentUser ||
     currentUser.role !== "BR"){
    return;
  }

  var card =
    document.getElementById(
      "managerLoanSettings"
    );

  if(card){
    card.style.display = "block";
  }

  var branch =
    db.branches.find(function(b){

      return (
        b.name === currentUser.branch ||
        b.id === currentUser.branchId
      );

    });

  if(!branch) return;


  var weekly =
    Number(
      branch.weeklyInterestRate
    );

  var monthly =
    Number(
      branch.monthlyInterestRate
    );


  if(isNaN(weekly)){
    weekly = 10;
  }

  if(isNaN(monthly)){
    monthly = 10;
  }


  document.getElementById(
    "managerWeeklyRate"
  ).value = weekly;


  document.getElementById(
    "managerMonthlyRate"
  ).value = monthly;

}


function saveManagerLoanRates(){

  if(!currentUser ||
     currentUser.role !== "BR"){

    alert("Only Manager can change loan rates.");
    return;

  }

  var weekly =
    Number(
      document.getElementById(
        "managerWeeklyRate"
      ).value
    );

  var monthly =
    Number(
      document.getElementById(
        "managerMonthlyRate"
      ).value
    );


  if(
    isNaN(weekly) ||
    isNaN(monthly) ||
    weekly < 0 ||
    monthly < 0
  ){

    alert("Please enter valid interest rates.");
    return;

  }


  var branch =
    db.branches.find(function(b){

      return (
        b.name === currentUser.branch ||
        b.id === currentUser.branchId
      );

    });


  if(!branch){

    alert("Manager branch not found.");
    return;

  }


  branch.weeklyInterestRate = weekly;

  branch.monthlyInterestRate = monthly;

  saveDB();

  alert(
    "Loan interest rates updated successfully.\n\n" +
    "Weekly: " + weekly + "%\n" +
    "Monthly: " + monthly + "%"
  );

  refreshAll();
  
}

if(pageId === "memberHomePage"){

  renderMemberTransactions();

  refreshMemberAccount();

}

if(pageId === "loanPageMember"){

  updateMemberLoanRate();

  calculateMemberLoan();

  renderMemberLoanHistory();

}

if(pageId === "earningPageMember"){

  renderMemberEarningHistory();

}

if(pageId === "accountPage" &&
   currentUser &&
   currentUser.role === "MB"){

  refreshMemberAccount();

}
/* =====================================================
   MEMBER APP
===================================================== */

function getLoggedMember(){

  if(!currentUser || currentUser.role !== "MB"){
    return null;
  }

  return db.members.find(function(m){

    return (
      m.id === currentUser.memberRecordId ||
      m.memberId === currentUser.memberId ||
      m.memberId === currentUser.code ||
      m.name === currentUser.name
    );

  });

}


/* =====================================================
   MEMBER HOME
===================================================== */

function toggleMemberForm(formId){

  var forms = [
    "memberSavingForm",
    "memberEmiForm"
  ];

  forms.forEach(function(id){

    var el = document.getElementById(id);

    if(!el) return;

    if(id === formId){

      el.classList.toggle("active");

    }else{

      el.classList.remove("active");

    }

  });

  if(formId === "memberEmiForm"){

    loadMemberEmiInfo();

  }

}


function memberAddSaving(){

  var member = getLoggedMember();

  if(!member){

    alert("Member account not found.");
    return;

  }

  var amount =
    Number(
      document.getElementById("memberSavingAmount").value
    );

  if(amount <= 0){

    alert("Enter valid saving amount.");
    return;

  }

  db.transactions.push({

    id:Date.now(),

    type:"Savings",

    branch:member.branch,

    member:member.name,

    memberId:member.memberId,

    amount:amount,

    date:new Date().toLocaleString()

  });

  saveDB();

  document.getElementById(
    "memberSavingAmount"
  ).value = "";

  document.getElementById(
    "memberSavingForm"
  ).classList.remove("active");

  refreshAll();

  alert(
    "Saving successfully added!\n\nAmount: ₹" +
    amount.toLocaleString("en-IN")
  );

}


/* =====================================================
   MEMBER EMI
===================================================== */

function getMemberActiveLoan(){

  var member = getLoggedMember();

  if(!member) return null;

  return db.loans.find(function(l){

    return (
      l.member === member.name &&
      l.branch === member.branch &&
      l.status === "Active"
    );

  });

}


function loadMemberEmiInfo(){

  var box =
    document.getElementById("memberEmiLoanInfo");

  var amountInput =
    document.getElementById("memberEmiAmount");

  if(!box) return;

  var loan = getMemberActiveLoan();

  if(!loan){

    box.innerHTML =
      '<span style="color:#dc3545;font-weight:bold;">' +
      'No active loan found.' +
      '</span>';

    if(amountInput){
      amountInput.value = "";
    }

    return;

  }

  var transactions =
    db.transactions.filter(function(t){

      return (
        t.type === "EMI Collect" &&
        t.loanId === loan.id
      );

    });

  var paidPrincipal =
    transactions.reduce(function(sum,t){

      return sum + Number(t.principal || 0);

    },0);

  var paidInterest =
    transactions.reduce(function(sum,t){

      return sum + Number(t.interest || 0);

    },0);

  var totalPaid =
    transactions.reduce(function(sum,t){

      return sum + Number(t.amount || 0);

    },0);

  var remaining =
    Math.max(
      0,
      Number(loan.totalPayable || loan.amount) -
      totalPaid
    );

  var parts =
    String(loan.duration || "1 Weeks").split(" ");

  var count =
    Number(parts[0]) || 1;

  var installment =
    Math.round(
      Number(loan.totalPayable || loan.amount) /
      count
    );

  box.innerHTML =

    "<b>Loan Amount:</b> ₹" +
    Number(loan.amount).toLocaleString("en-IN") +

    "<br><b>Interest:</b> " +
    Number(loan.interestRate || 0) + "%" +

    "<br><b>Total Payable:</b> ₹" +
    Number(loan.totalPayable || 0)
      .toLocaleString("en-IN") +

    "<br><b>Paid:</b> ₹" +
    totalPaid.toLocaleString("en-IN") +

    "<br><b>Remaining:</b> ₹" +
    remaining.toLocaleString("en-IN") +

    "<br><b>Suggested EMI:</b> ₹" +
    installment.toLocaleString("en-IN");

  if(amountInput){

    amountInput.value =
      remaining > 0
        ? Math.min(installment, remaining)
        : "";

  }

}


function memberPayEmi(){

  var member = getLoggedMember();

  if(!member){

    alert("Member account not found.");
    return;

  }

  var loan = getMemberActiveLoan();

  if(!loan){

    alert("No active loan found.");
    return;

  }

  var payment =
    Number(
      document.getElementById("memberEmiAmount").value
    );

  if(payment <= 0){

    alert("Enter valid EMI amount.");
    return;

  }

  var previousPayments =
    db.transactions.filter(function(t){

      return (
        t.type === "EMI Collect" &&
        t.loanId === loan.id
      );

    });

  var totalPaid =
    previousPayments.reduce(function(sum,t){

      return sum + Number(t.amount || 0);

    },0);

  var remainingTotal =
    Math.max(
      0,
      Number(loan.totalPayable || loan.amount) -
      totalPaid
    );

  if(payment > remainingTotal){

    alert(
      "EMI amount cannot be greater than remaining loan.\n\n" +
      "Remaining: ₹" +
      remainingTotal.toLocaleString("en-IN")
    );

    return;

  }

  var totalInterest =
    Math.max(
      0,
      Number(loan.totalPayable || 0) -
      Number(loan.amount || 0)
    );

  var paidInterest =
    previousPayments.reduce(function(sum,t){

      return sum + Number(t.interest || 0);

    },0);

  var paidPrincipal =
    previousPayments.reduce(function(sum,t){

      return sum + Number(t.principal || 0);

    },0);

  var remainingInterest =
    Math.max(0, totalInterest - paidInterest);

  var remainingPrincipal =
    Math.max(0, Number(loan.amount) - paidPrincipal);

  /* Interest first */

  var interestPay =
    Math.min(payment, remainingInterest);

  var principalPay =
    Math.min(
      payment - interestPay,
      remainingPrincipal
    );

  db.transactions.push({

    id:Date.now(),

    type:"EMI Collect",

    branch:member.branch,

    member:member.name,

    memberId:member.memberId,

    loanId:loan.id,

    principal:principalPay,

    interest:interestPay,

    amount:principalPay + interestPay,

    date:new Date().toLocaleString()

  });

  var newTotalPaid =
    totalPaid + payment;

  if(
    newTotalPaid >=
    Number(loan.totalPayable || loan.amount)
  ){

    loan.status = "Closed";

  }

  saveDB();

  document.getElementById(
    "memberEmiAmount"
  ).value = "";

  document.getElementById(
    "memberEmiForm"
  ).classList.remove("active");

  refreshAll();

  alert("EMI payment successfully saved.");

}


/* =====================================================
   MANAGER LOAN RATE
===================================================== */

function getMemberBranchObject(){

  var member = getLoggedMember();

  if(!member) return null;

  return db.branches.find(function(b){

    return (
      b.name === member.branch ||
      b.code === member.branchCode
    );

  });

}


function getManagerLoanRate(type){

  var branch = getMemberBranchObject();

  if(!branch){

    return 0;

  }

  if(type === "Weeks"){

    return Number(
      branch.weeklyInterestRate || 0
    );

  }

  return Number(
    branch.monthlyInterestRate || 0
  );

}


function updateMemberLoanRate(){

  var type =
    document.getElementById(
      "memberLoanType"
    ).value;

  var rate =
    getManagerLoanRate(type);

  var rateBox =
    document.getElementById(
      "memberLoanRate"
    );

  if(rateBox){

    rateBox.innerText =
      rate + "%";

  }

}


function calculateMemberLoan(){

  var amount =
    Number(
      document.getElementById(
        "memberLoanAmount"
      ).value
    ) || 0;

  var type =
    document.getElementById(
      "memberLoanType"
    ).value;

  var number =
    Number(
      document.getElementById(
        "memberLoanNumber"
      ).value
    ) || 0;

  var rate =
    getManagerLoanRate(type);

  var box =
    document.getElementById(
      "memberLoanCalculation"
    );

  if(!box) return;

  if(amount <= 0 || number <= 0){

    box.innerHTML =
      "Total Payable: ₹0<br>Installment: ₹0";

    return;

  }

  var interest =
    Math.round(
      amount * rate / 100
    );

  var total =
    amount + interest;

  var installment =
    Math.round(
      total / number
    );

  box.innerHTML =

    "<b>Loan Amount:</b> ₹" +
    amount.toLocaleString("en-IN") +

    "<br><b>Interest Rate:</b> " +
    rate + "%" +

    "<br><b>Total Interest:</b> ₹" +
    interest.toLocaleString("en-IN") +

    "<br><b>Total Payable:</b> ₹" +
    total.toLocaleString("en-IN") +

    "<br><b>Installment:</b> ₹" +
    installment.toLocaleString("en-IN");

}


/* =====================================================
   MEMBER APPLY LOAN
===================================================== */

function memberApplyLoan(){

  var member = getLoggedMember();

  if(!member){

    alert("Member account not found.");
    return;

  }

  var amount =
    Number(
      document.getElementById(
        "memberLoanAmount"
      ).value
    );

  var type =
    document.getElementById(
      "memberLoanType"
    ).value;

  var number =
    Number(
      document.getElementById(
        "memberLoanNumber"
      ).value
    );

  var rate =
    getManagerLoanRate(type);

  if(amount <= 0){

    alert("Please enter loan amount.");
    return;

  }

  if(number <= 0){

    alert("Please enter valid number.");
    return;

  }

  if(rate < 0){

    alert("Invalid manager loan rate.");
    return;

  }

  var activeLoan =
    getMemberActiveLoan();

  if(activeLoan){

    alert(
      "You already have an active loan."
    );

    return;

  }

  var totalInterest =
    Math.round(
      amount * rate / 100
    );

  var totalPayable =
    amount + totalInterest;

  var duration =
    number + " " + type;

  db.loanRequests.push({

    id:Date.now(),

    member:member.name,

    memberId:member.memberId,

    branch:member.branch,

    amount:amount,

    interestRate:rate,

    duration:duration,

    totalInterest:totalInterest,

    totalPayable:totalPayable,

    status:"Pending",

    date:new Date().toLocaleString()

  });

  saveDB();

  document.getElementById(
    "memberLoanAmount"
  ).value = "";

  document.getElementById(
    "memberLoanNumber"
  ).value = "";

  document.getElementById(
    "memberLoanCalculation"
  ).innerHTML =
    "Total Payable: ₹0<br>Installment: ₹0";

  renderMemberLoanHistory();

  alert(
    "Loan application submitted successfully.\n\n" +
    "Amount: ₹" +
    amount.toLocaleString("en-IN") +
    "\nRate: " +
    rate +
    "%\nDuration: " +
    duration +
    "\n\nStatus: Pending"
  );

}


/* =====================================================
   MEMBER LOAN HISTORY
===================================================== */

function renderMemberLoanHistory(){

  var list =
    document.getElementById(
      "memberLoanList"
    );

  if(!list) return;

  var member = getLoggedMember();

  if(!member){

    list.innerHTML =
      '<div class="empty">Member not found</div>';

    return;

  }

  var searchEl =
    document.getElementById(
      "memberLoanSearch"
    );

  var search =
    searchEl
      ? searchEl.value.toLowerCase()
      : "";

  var requests =
    db.loanRequests.filter(function(r){

      return (
        r.member === member.name &&
        r.branch === member.branch
      );

    });

  var loans =
    db.loans.filter(function(l){

      return (
        l.member === member.name &&
        l.branch === member.branch
      );

    });

  var html = "";

  loans.slice().reverse().forEach(function(l){

    var paid =
      db.transactions
        .filter(function(t){

          return (
            t.type === "EMI Collect" &&
            t.loanId === l.id
          );

        })
        .reduce(function(sum,t){

          return sum + Number(t.amount || 0);

        },0);

    var remaining =
      Math.max(
        0,
        Number(l.totalPayable || l.amount) -
        paid
      );

    var text =
      (
        "loan " +
        l.duration +
        " " +
        l.status
      ).toLowerCase();

    if(search && text.indexOf(search) === -1){
      return;
    }

    html +=

      '<div class="item">' +

      '<div>' +

      '<b>💳 Loan</b>' +

      '<br><small>Amount: ₹' +
      Number(l.amount).toLocaleString("en-IN") +
      '</small>' +

      '<br><small>Interest: ' +
      Number(l.interestRate || 0) +
      '%</small>' +

      '<br><small>Duration: ' +
      l.duration +
      '</small>' +

      '<br><small>Total Payable: ₹' +
      Number(l.totalPayable || 0)
        .toLocaleString("en-IN") +
      '</small>' +

      '<br><small>Remaining: ₹' +
      remaining.toLocaleString("en-IN") +
      '</small>' +

      '<br><small style="color:#777;">' +
      l.date +
      '</small>' +

      '</div>' +

      '<div>' +

      '<b style="color:' +
      (l.status === "Active"
        ? "#198754"
        : "#777") +
      ';">' +

      l.status +

      '</b>' +

      '</div>' +

      '</div>';

  });


  requests.slice().reverse().forEach(function(r){

    var text =
      (
        "loan request " +
        r.duration +
        " " +
        r.status
      ).toLowerCase();

    if(search && text.indexOf(search) === -1){
      return;
    }

    html +=

      '<div class="item">' +

      '<div>' +

      '<b>📄 Loan Request</b>' +

      '<br><small>Amount: ₹' +
      Number(r.amount).toLocaleString("en-IN") +
      '</small>' +

      '<br><small>Rate: ' +
      Number(r.interestRate || 0) +
      '%</small>' +

      '<br><small>Duration: ' +
      r.duration +
      '</small>' +

      '<br><small>Total Payable: ₹' +
      Number(r.totalPayable || 0)
        .toLocaleString("en-IN") +
      '</small>' +

      '<br><small style="color:#777;">' +
      r.date +
      '</small>' +

      '</div>' +

      '<div>' +

      '<b style="color:#f59f00;">' +
      r.status +
      '</b>' +

      '</div>' +

      '</div>';

  });


  if(!html){

    html =
      '<div class="empty">' +
      'No loan history found' +
      '</div>';

  }

  list.innerHTML = html;

}


/* =====================================================
   MEMBER EARNING
===================================================== */

function getMemberSelfEarning(){

  var member = getLoggedMember();

  if(!member) return 0;

  return db.transactions
    .filter(function(t){

      return (
        t.type === "Distribute" &&
        t.member === member.name &&
        t.branch === member.branch
      );

    })
    .reduce(function(sum,t){

      return sum + Number(t.amount || 0);

    },0);

}


function getMemberEarningWithdrawal(){

  var member = getLoggedMember();

  if(!member) return 0;

  return db.transactions
    .filter(function(t){

      return (
        t.type === "Earning Withdrawal" &&
        t.member === member.name &&
        t.branch === member.branch
      );

    })
    .reduce(function(sum,t){

      return sum + Number(t.amount || 0);

    },0);

}


function getMemberAvailableEarning(){

  return Math.max(
    0,
    getMemberSelfEarning() -
    getMemberEarningWithdrawal()
  );

}


/* =====================================================
   EARNING REQUEST
===================================================== */

function requestEarningWithdrawal(){

  var member = getLoggedMember();

  if(!member){

    alert("Member account not found.");
    return;

  }

  var amount =
    Number(
      document.getElementById(
        "earningRequestAmount"
      ).value
    );

  var available =
    getMemberAvailableEarning();

  if(amount <= 0){

    alert("Enter valid amount.");
    return;

  }

  if(amount > available){

    alert(
      "Insufficient earning.\n\n" +
      "Available Earning: ₹" +
      available.toLocaleString("en-IN")
    );

    return;

  }

  db.earningRequests.push({

    id:Date.now(),

    member:member.name,

    memberId:member.memberId,

    branch:member.branch,

    amount:amount,

    status:"Pending",

    date:new Date().toLocaleString()

  });

  saveDB();

  document.getElementById(
    "earningRequestAmount"
  ).value = "";

  renderMemberEarningHistory();

  alert(
    "Earning withdrawal request submitted.\n\n" +
    "Amount: ₹" +
    amount.toLocaleString("en-IN") +
    "\nStatus: Pending"
  );

}


/* =====================================================
   MEMBER EARNING HISTORY
===================================================== */

function renderMemberEarningHistory(){

  var list =
    document.getElementById(
      "memberEarningsList"
    );

  if(!list) return;

  var member = getLoggedMember();

  if(!member) return;

  var selfEarning =
    getMemberSelfEarning();

  var withdrawal =
    getMemberEarningWithdrawal();

  var available =
    Math.max(
      0,
      selfEarning - withdrawal
    );

  document.getElementById(
    "memberSelfEarning"
  ).innerText =
    "₹" +
    selfEarning.toLocaleString("en-IN");

  document.getElementById(
    "memberEarningWithdrawal"
  ).innerText =
    "₹" +
    withdrawal.toLocaleString("en-IN");

  document.getElementById(
    "memberAvailableEarning"
  ).innerText =
    "₹" +
    available.toLocaleString("en-IN");


  var searchEl =
    document.getElementById(
      "memberEarningSearch"
    );

  var search =
    searchEl
      ? searchEl.value.toLowerCase()
      : "";

  var history = [];


  db.transactions
    .filter(function(t){

      return (
        t.type === "Distribute" &&
        t.member === member.name &&
        t.branch === member.branch
      );

    })
    .forEach(function(t){

      history.push({

        date:t.date,

        type:"Self Earning",

        amount:Number(t.amount || 0),

        status:"Credited",

        description:
          t.description || "Profit Distribution"

      });

    });


  db.transactions
    .filter(function(t){

      return (
        t.type === "Earning Withdrawal" &&
        t.member === member.name &&
        t.branch === member.branch
      );

    })
    .forEach(function(t){

      history.push({

        date:t.date,

        type:"Earning Withdrawal",

        amount:Number(t.amount || 0),

        status:"Withdrawn",

        description:
          t.description || "Earning Withdrawal"

      });

    });


  db.earningRequests
    .filter(function(r){

      return (
        r.member === member.name &&
        r.branch === member.branch
      );

    })
    .forEach(function(r){

      history.push({

        date:r.date,

        type:"Withdrawal Request",

        amount:Number(r.amount || 0),

        status:r.status,

        description:"Earning Withdrawal Request"

      });

    });


  history.reverse();


  var html = "";

  history.forEach(function(h){

    var text =
      (
        h.type +
        " " +
        h.description +
        " " +
        h.status
      ).toLowerCase();

    if(search && text.indexOf(search) === -1){
      return;
    }

    var negative =
      h.type === "Earning Withdrawal";

    html +=

      '<div class="item">' +

      '<div>' +

      '<b>💸 ' +
      h.type +
      '</b>' +

      '<br><small>' +
      h.description +
      '</small>' +

      '<br><small style="color:#777;">' +
      h.date +
      '</small>' +

      '</div>' +

      '<div style="text-align:right;">' +

      '<b style="color:' +
      (negative
        ? "#dc3545"
        : "#198754") +
      ';font-size:17px;">' +

      (negative ? "-" : "+") +
      "₹" +
      h.amount.toLocaleString("en-IN") +

      '</b>' +

      '<br><small>' +
      h.status +
      '</small>' +

      '</div>' +

      '</div>';

  });


  if(!html){

    html =
      '<div class="empty">' +
      'No earning history found' +
      '</div>';

  }

  list.innerHTML = html;

}


/* =====================================================
   MEMBER TRANSACTIONS
===================================================== */

function renderMemberTransactions(){

  var list =
    document.getElementById(
      "memberTransactionList"
    );

  if(!list) return;

  var member = getLoggedMember();

  if(!member){

    list.innerHTML =
      '<div class="empty">Member not found</div>';

    return;

  }

  var searchEl =
    document.getElementById(
      "memberTransactionSearch"
    );

  var search =
    searchEl
      ? searchEl.value.toLowerCase()
      : "";

  var transactions =
    db.transactions
      .filter(function(t){

        return (
          t.member === member.name &&
          t.branch === member.branch
        );

      })
      .slice()
      .reverse();

  var html = "";

  transactions.forEach(function(t){

    var text =
      (
        t.type +
        " " +
        (t.description || "")
      ).toLowerCase();

    if(search && text.indexOf(search) === -1){
      return;
    }

    var isOut =
      t.type === "New Loan" ||
      t.type === "Other OUT" ||
      t.type === "Distribute" ||
      t.type === "Earning Withdrawal";

    var sign =
      isOut ? "-" : "+";

    var color =
      isOut ? "#dc3545" : "#198754";

    html +=

      '<div class="item">' +

      '<div>' +

      '<b>' +
      t.type +
      '</b>' +

      (t.type === "EMI Collect"
        ? '<br><small>Principal: ₹' +
          Number(t.principal || 0)
            .toLocaleString("en-IN") +
          ' | Interest: ₹' +
          Number(t.interest || 0)
            .toLocaleString("en-IN") +
          '</small>'
        : "") +

      (t.duration
        ? '<br><small>Duration: ' +
          t.duration +
          '</small>'
        : "") +

      (t.description
        ? '<br><small>' +
          t.description +
          '</small>'
        : "") +

      '<br><small style="color:#777;">' +
      t.date +
      '</small>' +

      '</div>' +

      '<div style="text-align:right;">' +

      '<b style="color:' +
      color +
      ';font-size:17px;">' +

      sign +
      "₹" +
      Number(t.amount || 0)
        .toLocaleString("en-IN") +

      '</b>' +

      '</div>' +

      '</div>';

  });


  if(!html){

    html =
      '<div class="empty">' +
      'No transactions found' +
      '</div>';

  }

  list.innerHTML = html;

}
function refreshMemberAccount(){

  if(!currentUser ||
     currentUser.role !== "MB"){
    return;
  }

  var member = getLoggedMember();

  if(!member) return;


  /* TOTAL SAVINGS */

  var totalSavings =
    db.transactions
      .filter(function(t){

        return (
          t.type === "Savings" &&
          t.member === member.name &&
          t.branch === member.branch
        );

      })
      .reduce(function(sum,t){

        return sum + Number(t.amount || 0);

      },0);


  /* PRINCIPAL PAID */

  var principalPaid =
    db.transactions
      .filter(function(t){

        return (
          t.type === "EMI Collect" &&
          t.member === member.name &&
          t.branch === member.branch
        );

      })
      .reduce(function(sum,t){

        return sum + Number(t.principal || 0);

      },0);


  /* LOAN PRINCIPAL */

  var loanPrincipal =
    db.transactions
      .filter(function(t){

        return (
          t.type === "New Loan" &&
          t.member === member.name &&
          t.branch === member.branch
        );

      })
      .reduce(function(sum,t){

        return sum + Number(t.amount || 0);

      },0);


  /*
    CURRENT SAVINGS
    = Total Savings
      + Principal EMI
      - Loan Principal
  */

  var currentSavings =
    totalSavings +
    principalPaid -
    loanPrincipal;

  if(currentSavings < 0){
    currentSavings = 0;
  }


  /* EARNING */

  var selfEarning =
    getMemberSelfEarning();

  var earningWithdrawal =
    getMemberEarningWithdrawal();

  var earning =
    Math.max(
      0,
      selfEarning -
      earningWithdrawal
    );


  /* TOTAL BALANCE */

  var totalBalance =
    currentSavings +
    earning;


  document.getElementById(
    "accountMemberTotalSavings"
  ).innerText =
    "₹" +
    totalSavings.toLocaleString("en-IN");


  document.getElementById(
    "accountMemberCurrentSavings"
  ).innerText =
    "₹" +
    currentSavings.toLocaleString("en-IN");


  document.getElementById(
    "accountMemberEarning"
  ).innerText =
    "₹" +
    earning.toLocaleString("en-IN");


  document.getElementById(
    "accountMemberTotalBalance"
  ).innerText =
    "₹" +
    totalBalance.toLocaleString("en-IN");


  var homeBalance =
    document.getElementById(
      "memberHomeTotalBalance"
    );

  if(homeBalance){

    homeBalance.innerText =
      "₹" +
      totalBalance.toLocaleString("en-IN");

  }

}
/* ===================================================== NAVIGATION ===================================================== */
function openPage(pageId, button){
  document.querySelectorAll(".page").forEach(function(page){
    page.style.display = "none";
    page.classList.remove("active");
  });
  var page = document.getElementById(pageId);
  if(page){
    page.style.display = "block";
    page.classList.add("active");
  }
  closeMenu();
  document.querySelectorAll(".bottom-nav .nav-btn").forEach(function(btn){
    btn.classList.remove("active");
  });
  if(button){
    button.classList.add("active");
  } else {
    var buttons = document.querySelectorAll(".bottom-nav .nav-btn");
    buttons.forEach(function(btn){
      if(btn.getAttribute("onclick") && btn.getAttribute("onclick").indexOf(pageId) !== -1){
        btn.classList.add("active");
      }
    });
  }
  if(pageId === "teamPage"){
    populateMemberBranchDropdown();
    if(currentUser && currentUser.role === "MB"){
      document.getElementById("addMemberFormBox").style.display = "none";
    }
  }
  if(pageId === "distributePage"){
    setupDistributePageUI();
    filterDistributeMembers();
    updateDistributionAvailableBalance();
  }
}

function toggleNotifModal(show){
  document.getElementById("notifModal").style.display = show ? "flex" : "none";
}

function toggleForm(formId){
  var forms = [ "formSavings", "formLoan", "formEmi", "formOthers" ];
  forms.forEach(function(id){
    var el = document.getElementById(id);
    if(id === formId){
      el.classList.toggle("active");
    } else{
      el.classList.remove("active");
    }
  });
  var selected = document.getElementById(formId);
  if(selected && selected.classList.contains("active")){
    populateBranchDropdowns();
  }
}

/* ===================================================== DROPDOWNS & BRANCHES ===================================================== */
function populateBranchDropdowns(){
  var branchSelects = [ "savBranch", "loanBranch", "emiBranch" ];
  branchSelects.forEach(function(id){
    var el = document.getElementById(id);
    if(el){
      el.innerHTML = '<option value="">Select Branch First</option>';
      var branchesToUse = db.branches;
      if(currentUser && currentUser.role === "BR"){
        branchesToUse = db.branches.filter(function(b){ return b.name === currentUser.branch; });
      }
      branchesToUse.forEach(function(b){
        el.innerHTML += '<option value="' + b.name + '">' + b.name + " (" + b.code + ")" + "</option>";
      });
    }
  });
}

function filterMembersByBranch(branchSelectId, memberSelectId){
  var branchEl = document.getElementById(branchSelectId);
  var memberSelect = document.getElementById(memberSelectId);
  if(!branchEl || !memberSelect){ return; }
  var selectedBranch = branchEl.value;
  memberSelect.innerHTML = '<option value="">Select Member</option>';
  if(!selectedBranch){ return; }
  db.members.filter(function(m){
    return m.branch === selectedBranch;
  }).forEach(function(m){
    memberSelect.innerHTML += '<option value="' + m.name + '">' + m.name + " - " + m.memberId + "</option>";
  });
}

function populateMemberBranchDropdown(){
  var el = document.getElementById("memberBranch");
  if(!el){ return; }
  el.innerHTML = '<option value="">Select Branch</option>';
  var branchesToUse = db.branches;
  if(currentUser && currentUser.role === "BR"){
    branchesToUse = db.branches.filter(function(b){ return b.name === currentUser.branch; });
  }
  branchesToUse.forEach(function(b){
    el.innerHTML += '<option value="' + b.name + '">' + b.name + " (" + b.code + ")" + "</option>";
  });
}

function filterDropdown(searchId, selectId){
  var searchEl = document.getElementById(searchId);
  var select = document.getElementById(selectId);
  if(!searchEl || !select){ return; }
  var filter = searchEl.value.toLowerCase();
  var options = select.options;
  for(var i = 0; i < options.length; i++){
    var text = options[i].text.toLowerCase();
    var val = options[i].value.toLowerCase();
    if(text.indexOf(filter) !== -1 || val.indexOf(filter) !== -1 || options[i].value === ""){
      options[i].style.display = "";
    } else {
      options[i].style.display = "none";
    }
  }
}

/* ===================================================== CALCULATIONS ===================================================== */
function calculateEmiTotal(){
  var p = Number(document.getElementById("emiPrincipal").value) || 0;
  var i = Number(document.getElementById("emiInterest").value) || 0;
  var total = p + i;
  document.getElementById("emiTotalDisplay").innerText = "₹" + total.toLocaleString("en-IN");
}

function calculateLoanEmiPreview(){
  var amt = Number(document.getElementById("amtLoan").value) || 0;
  var rate = Number(document.getElementById("loanInterestRate").value) || 0;
  var val = Number(document.getElementById("loanDurationVal").value) || 1;
  if(val <= 0){ val = 1; }
  var totalInterest = Math.round(amt * (rate / 100));
  var totalPayable = amt + totalInterest;
  var estEmi = Math.round(totalPayable / val);
  document.getElementById("loanEmiPreviewBox").innerText = "Total Payable: ₹" + totalPayable.toLocaleString("en-IN") + " | Installment: ₹" + estEmi.toLocaleString("en-IN");
}

function loadMemberActiveLoan(){
  var memberName = document.getElementById("emiMember").value;
  var infoBox = document.getElementById("memberLoanInfo");
  if(!memberName){
    infoBox.style.display = "none";
    return;
  }
  var loan = db.loans.find(function(l){
    return (l.member === memberName && l.status === "Active");
  });
  if(loan){
    var totalPaidPrincipal = db.transactions.filter(function(t){
      return (t.type === "EMI Collect" && t.member === memberName && t.loanId === loan.id);
    }).reduce(function(sum,t){
      return sum + Number(t.principal || 0);
    }, 0);
    var remainingBalance = loan.totalPayable - totalPaidPrincipal;
    var valParts = String(loan.duration).split(" ");
    var count = Number(valParts[0]) || 1;
    var principalPerInstallment = Math.round(loan.amount / count);
    var interestPerInstallment = Math.round((loan.totalPayable - loan.amount) / count);
    var perInstallment = principalPerInstallment + interestPerInstallment;

    infoBox.style.display = "block";
    infoBox.innerHTML = "<b>Loan Total:</b> ₹" + loan.totalPayable.toLocaleString("en-IN") + " | <b>Remaining Balance:</b> ₹" + remainingBalance.toLocaleString("en-IN") + "<br><b>Suggested Installment:</b> ₹" + perInstallment.toLocaleString("en-IN") + " (P: ₹" + principalPerInstallment + " + I: ₹" + interestPerInstallment + ")";
    
    var remainingPrincipal = Math.max(0, loan.amount - totalPaidPrincipal);
    document.getElementById("emiPrincipal").value = Math.min(principalPerInstallment, remainingPrincipal);
    document.getElementById("emiInterest").value = interestPerInstallment;
    calculateEmiTotal();
  } else {
    infoBox.style.display = "block";
    infoBox.innerHTML = "No active loan found for this member.";
  }
}

function payFromNotification(branchName, memberName){
  toggleNotifModal(false);
  openPage('homePage');
  toggleForm("formEmi");
  var branchSelect = document.getElementById("emiBranch");
  branchSelect.value = branchName;
  filterMembersByBranch("emiBranch", "emiMember");
  setTimeout(function(){
    var memberSelect = document.getElementById("emiMember");
    memberSelect.value = memberName;
    loadMemberActiveLoan();
  }, 100);
}

function checkReminders(){
  var badge = document.getElementById("notifBadge");
  var contentBox = document.getElementById("notifListContent");
  var reminders = [];
  var loansToCheck = db.loans;
  if(currentUser && currentUser.role === "BR"){
    loansToCheck = db.loans.filter(function(l){ return l.branch === currentUser.branch; });
  } else if(currentUser && currentUser.role === "MB"){
    loansToCheck = db.loans.filter(function(l){ return l.member === currentUser.name; });
  }
if(currentUser && currentUser.role === "MB"){

  refreshMemberAccount();

  renderMemberTransactions();

  renderMemberLoanHistory();

  renderMemberEarningHistory();

  updateMemberLoanRate();

  var activeLoan = getMemberActiveLoan();

  var activeLoanValue = 0;

  if(activeLoan){

    var paid =
      db.transactions
        .filter(function(t){

          return (
            t.type === "EMI Collect" &&
            t.loanId === activeLoan.id
          );

        })
        .reduce(function(sum,t){

          return sum + Number(t.amount || 0);

        },0);

    activeLoanValue =
      Math.max(
        0,
        Number(
          activeLoan.totalPayable ||
          activeLoan.amount
        ) - paid
      );

  }

  var loanBox =
    document.getElementById(
      "memberActiveLoanVal"
    );

  if(loanBox){

    loanBox.innerText =
      "₹" +
      activeLoanValue.toLocaleString("en-IN");

  }

}
  loansToCheck.forEach(function(l){
    if(l.status === "Active"){
      var totalPaid = db.transactions.filter(function(t){
        return (t.type === "EMI Collect" && t.member === l.member && t.loanId === l.id);
      }).reduce(function(sum,t){
        return sum + Number(t.amount || 0);
      }, 0);
      var remainingDue = (l.totalPayable || l.amount) - totalPaid;
      if(remainingDue < 0){ remainingDue = 0; }
      var valParts = String(l.duration).split(" ");
      var count = Number(valParts[0]) || 1;
      var installmentAmt = Math.round((l.totalPayable || l.amount) / count);

      reminders.push('<div style="padding:12px 0;border-bottom:1px solid #eee;"><div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:6px;"><div><b>' + l.member + '</b><br><small style="color:#777;">Branch: ' + l.branch + '</small></div><div style="text-align:right;"><span style="color:#dc3545;font-weight:bold;">Due: ₹' + installmentAmt.toLocaleString("en-IN") + '</span><br><small style="color:#555;">Bal: ₹' + remainingDue.toLocaleString("en-IN") + '</small></div></div><button style="width:100%;background:#198754;color:white;padding:8px;font-size:13px;border-radius:6px;font-weight:bold;" onclick="payFromNotification(\'' + String(l.branch).replace(/'/g,"\\'") + '\',\'' + String(l.member).replace(/'/g,"\\'") + '\')">Pay Now</button></div>');
    }
  });

  if(reminders.length > 0){
    badge.style.display = "flex";
    badge.innerText = reminders.length;
    contentBox.innerHTML = reminders.join("");
  } else {
    badge.style.display = "none";
    contentBox.innerHTML = "No active reminders.";
  }
}

/* ===================================================== TRANSACTIONS & MODULES ===================================================== */
function addSavingsTrans(){
  var branch = document.getElementById("savBranch").value;
  var member = document.getElementById("savMember").value;
  var amount = Number(document.getElementById("amtSavings").value);
  if(!branch || !member || amount <= 0){
    alert("Please select branch, member and enter valid amount");
    return;
  }
  db.transactions.push({
    id:Date.now(),
    type:"Savings",
    branch:branch,
    member:member,
    amount:amount,
    date:new Date().toLocaleString()
  });
  saveDB();
  document.getElementById("amtSavings").value = "";
  document.getElementById("formSavings").classList.remove("active");
  refreshAll();
}

function addNewLoanTrans(){
  var branch = document.getElementById("loanBranch").value;
  var member = document.getElementById("loanMemberSel").value;
  var amount = Number(document.getElementById("amtLoan").value);
  var rate = Number(document.getElementById("loanInterestRate").value) || 0;
  var durationType = document.getElementById("loanDurationType").value;
  var durationVal = document.getElementById("loanDurationVal").value;
  if(!branch || !member || amount <= 0 || !durationVal){
    alert("Please fill all loan details properly");
    return;
  }

  var savingsAmount = db.transactions.filter(function(t){ return t.type === "Savings"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var principalEMI = db.transactions.filter(function(t){ return t.type === "EMI Collect"; }).reduce(function(sum,t){ return sum + Number(t.principal || 0); }, 0);
  var existingNewLoans = db.transactions.filter(function(t){ return t.type === "New Loan"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var availableSavings = savingsAmount + principalEMI - existingNewLoans;

  if(amount > availableSavings){
    alert("Loan cannot be issued!\n\nAvailable Savings: ₹" + availableSavings.toLocaleString("en-IN") + "\nLoan Amount: ₹" + amount.toLocaleString("en-IN"));
    return;
  }

  var totalInterest = Math.round(amount * (rate / 100));
  var totalPayable = amount + totalInterest;
  var durationStr = durationVal + " " + durationType;
  var loanId = Date.now();

  db.transactions.push({
    id:loanId,
    type:"New Loan",
    branch:branch,
    member:member,
    duration:durationStr,
    amount:amount,
    date:new Date().toLocaleString()
  });

  db.loans.push({
    id:loanId,
    member:member,
    branch:branch,
    amount:amount,
    interestRate:rate,
    totalPayable:totalPayable,
    duration:durationStr,
    status:"Active",
    date:new Date().toLocaleDateString()
  });

  saveDB();
  document.getElementById("amtLoan").value = "";
  document.getElementById("loanDurationVal").value = "";
  document.getElementById("formLoan").classList.remove("active");
  refreshAll();
}

function addEmiTrans(){
  var branch = document.getElementById("emiBranch").value;
  var member = document.getElementById("emiMember").value;
  var principal = Number(document.getElementById("emiPrincipal").value) || 0;
  var interest = Number(document.getElementById("emiInterest").value) || 0;
  var total = principal + interest;

  if(!branch || !member || total <= 0){
    alert("Please select branch, member and enter valid amounts");
    return;
  }

  var activeLoan = db.loans.find(function(l){ return (l.member === member && l.status === "Active"); });
  var loanId = activeLoan ? activeLoan.id : null;

  db.transactions.push({
    id:Date.now(),
    type:"EMI Collect",
    branch:branch,
    member:member,
    loanId:loanId,
    principal:principal,
    interest:interest,
    amount:total,
    date:new Date().toLocaleString()
  });

  if(activeLoan){
    var totalPaidPrincipal = db.transactions.filter(function(t){
      return (t.type === "EMI Collect" && t.member === member && t.loanId === activeLoan.id);
    }).reduce(function(sum,t){
      return sum + Number(t.principal || 0);
    }, 0);

    if(totalPaidPrincipal >= activeLoan.amount){
      activeLoan.status = "Closed";
    }
  }

  saveDB();
  document.getElementById("emiPrincipal").value = "";
  document.getElementById("emiInterest").value = "";
  document.getElementById("emiTotalDisplay").innerText = "₹0";
  document.getElementById("formEmi").classList.remove("active");
  refreshAll();
}

function addQuickTransOthers(){
  var subType = document.getElementById("typeOthers").value;
  var amount = Number(document.getElementById("amtOthers").value);
  var desc = document.getElementById("descOthers").value.trim();
  if(amount <= 0){
    alert("Enter valid amount");
    return;
  }
  if(subType === "Other OUT"){
    var currentBalance = Number(document.getElementById("totalRemainingBalance").innerText.replace(/[₹,]/g,""));
    if(amount > currentBalance){
      alert("Insufficient Balance! Available Balance: ₹" + currentBalance.toLocaleString("en-IN"));
      return;
    }
  }
  db.transactions.push({
    id:Date.now(),
    type:subType,
    amount:amount,
    description:desc,
    date:new Date().toLocaleString()
  });
  saveDB();
  document.getElementById("amtOthers").value = "";
  document.getElementById("descOthers").value = "";
  document.getElementById("formOthers").classList.remove("active");
  refreshAll();
}

function addBranch(){
  var name = document.getElementById("branchName").value.trim();
  var manager = document.getElementById("branchManager").value.trim();
  var managerPassword = document.getElementById("branchManagerPassword").value;
  var mobile = document.getElementById("branchMobile").value.trim();
  var address = document.getElementById("branchAddress").value.trim();

  if(!name || !manager || !managerPassword || !mobile || !address){
    alert("Please fill all fields");
    return;
  }

  var managerNumber = 1;
  while(db.users.some(function(u){ return (u.username === "MG" + fourDigit(managerNumber)); })){
    managerNumber++;
  }
  var managerCode = "MG" + fourDigit(managerNumber);
  var branchNumber = db.branches.length + 1;
  var branchCode = "BRN-" + (100 + branchNumber);
  var branchId = Date.now();

  db.branches.push({

  id:branchId,

  name:name,

  manager:manager,

  mobile:mobile,

  address:address,

  code:branchCode,

  managerCode:managerCode,

  weeklyInterestRate:10,

  monthlyInterestRate:10,

  joinDate:new Date().toLocaleDateString()

});

  db.users.push({
    id:Date.now() + 1,
    name:manager,
    username:managerCode,
    password:managerPassword,
    role:"BR",
    branch:name,
    branchCode:branchCode,
    branchId:branchId,
    joinDate: new Date().toLocaleDateString(),
    code:managerCode
  });

  saveDB();
  document.getElementById("branchName").value = "";
  document.getElementById("branchManager").value = "";
  document.getElementById("branchManagerPassword").value = "";
  document.getElementById("branchMobile").value = "";
  document.getElementById("branchAddress").value = "";
  refreshAll();
  alert("Branch created successfully!\n\nManager Code: " + managerCode + "\nPassword: " + managerPassword);
}

function addMember(){
  var branch = document.getElementById("memberBranch").value;
  var name = document.getElementById("memberName").value.trim();
  var mobile = document.getElementById("memberMobile").value.trim();
  var address = document.getElementById("memberAddress").value.trim();
  var password = document.getElementById("memberPassword").value;

  if(!branch || !name || !mobile || !address || !password){
    alert("Please fill all fields");
    return;
  }

  var memberNumber = 1;
  while(db.users.some(function(u){ return (u.username === "MB" + fourDigit(memberNumber)); })){
    memberNumber++;
  }
  var memberCode = "MB" + fourDigit(memberNumber);
  var memberId = Date.now();
  var branchObj = db.branches.find(function(b){ return b.name === branch; });

  db.members.push({
    id:memberId,
    branch:branch,
    name:name,
    mobile:mobile,
    address:address,
    memberId:memberCode,
    branchCode: branchObj ? branchObj.code : "",
    managerCode: branchObj ? branchObj.managerCode : "",
    joinDate: new Date().toLocaleDateString()
  });

  db.users.push({
    id:Date.now() + 1,
    name:name,
    username:memberCode,
    password:password,
    role:"MB",
    branch:branch,
    memberId:memberCode,
    memberRecordId:memberId,
    branchCode: branchObj ? branchObj.code : "",
    joinDate: new Date().toLocaleDateString(),
    code:memberCode
  });

  saveDB();
  document.getElementById("memberName").value = "";
  document.getElementById("memberMobile").value = "";
  document.getElementById("memberAddress").value = "";
  document.getElementById("memberPassword").value = "";
  refreshAll();
  alert("Member added successfully!\n\nMember Code: " + memberCode + "\nPassword: " + password);
}

function setupLongPress(element, onDelete){
  var timer = null;
  function startPress(){
    timer = setTimeout(function(){ onDelete(); }, 800);
  }
  function cancelPress(){
    if(timer){ clearTimeout(timer); timer = null; }
  }
  element.addEventListener("touchstart", startPress, {passive:true});
  element.addEventListener("touchend", cancelPress);
  element.addEventListener("touchcancel", cancelPress);
  element.addEventListener("touchmove", cancelPress);
  element.addEventListener("mousedown", startPress);
  element.addEventListener("mouseup", cancelPress);
  element.addEventListener("mouseleave", cancelPress);
}

function refreshAll(){
  var savingsAmount = db.transactions.filter(function(t){ return t.type === "Savings"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var principalEMI = db.transactions.filter(function(t){ return t.type === "EMI Collect"; }).reduce(function(sum,t){ return sum + Number(t.principal || 0); }, 0);
  var interest = db.transactions.filter(function(t){ return t.type === "EMI Collect"; }).reduce(function(sum,t){ return sum + Number(t.interest || 0); }, 0);
  var otherIn = db.transactions.filter(function(t){ return t.type === "Other IN"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var otherOut = db.transactions.filter(function(t){ return t.type === "Other OUT"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var totalDistributed = db.transactions.filter(function(t){ return t.type === "Distribute"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var newLoanPrincipal = db.transactions.filter(function(t){ return t.type === "New Loan"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);

  var availableSavings = savingsAmount + principalEMI - newLoanPrincipal;
  var earningsBalance = interest + otherIn - otherOut - totalDistributed;
  var totalBalance = availableSavings + earningsBalance;

  var activeLoanBalance = db.loans.filter(function(l){ return l.status === "Active"; }).reduce(function(sum,l){
    var paidPrincipal = db.transactions.filter(function(t){
      return (t.type === "EMI Collect" && t.loanId === l.id);
    }).reduce(function(s,t){ return s + Number(t.principal || 0); }, 0);
    var remainingPrincipal = Number(l.amount || 0) - paidPrincipal;
        return sum + Math.max(0, Number(l.amount || 0) - paidPrincipal);
  }, 0);

  document.getElementById("totalBalance").innerText = "₹" + totalBalance.toLocaleString("en-IN");
  document.getElementById("totalSavings").innerText = "₹" + savingsAmount.toLocaleString("en-IN");
  document.getElementById("availableSavings").innerText = "₹" + availableSavings.toLocaleString("en-IN");
  document.getElementById("totalRemainingBalance").innerText = "₹" + earningsBalance.toLocaleString("en-IN");
  document.getElementById("totalLoan").innerText = "₹" + activeLoanBalance.toLocaleString("en-IN");

  renderTransactions();
  renderBranches();
  renderMembers();
  renderDistributions();
  checkReminders();
  updateRealTimeBadges();
}

/* ===================================================== RENDER LISTS ===================================================== */
function renderTransactions(){
  var list = document.getElementById("transactionList");
  var searchInput = document.getElementById("searchTransactionInput");
  var search = searchInput ? searchInput.value.toLowerCase() : "";
  var html = "";

  db.transactions.slice().reverse().forEach(function(t, idx){
    var actualIndex = db.transactions.length - 1 - idx;
    var searchStr = (t.type + " " + (t.member || "") + " " + (t.branch || "") + " " + (t.description || "")).toLowerCase();
    if(search && searchStr.indexOf(search) === -1){ return; }

    var isOut = t.type === "New Loan" || t.type === "Other OUT" || t.type === "Distribute" || t.type === "Earning Withdrawal";
    var sign = isOut ? "-" : "+";
    var color = isOut ? "#dc3545" : "#198754";

    html += '<div class="item" id="trans-item-' + actualIndex + '">' +
            '<div>' +
            '<b>' + t.type + '</b>' +
            (t.branch ? '<br><small>Branch: ' + t.branch + '</small>' : '') +
            (t.member ? '<br><small>Member: ' + t.member + '</small>' : '') +
            (t.type === "EMI Collect" ? '<br><small>Principal: ₹' + Number(t.principal || 0).toLocaleString("en-IN") + ' | Interest: ₹' + Number(t.interest || 0).toLocaleString("en-IN") + '</small>' : '') +
            (t.duration ? '<br><small>Duration: ' + t.duration + '</small>' : '') +
            (t.description ? '<br><small>' + t.description + '</small>' : '') +
            '<br><small style="color:#777;">' + t.date + '</small>' +
            '</div>' +
            '<div style="text-align:right;">' +
            '<b style="color:' + color + ';font-size:17px;">' + sign + '₹' + Number(t.amount || 0).toLocaleString("en-IN") + '</b>' +
            '</div>' +
            '</div>';
  });

  if(!html){
    html = '<div class="empty">No transactions found</div>';
  }
  list.innerHTML = html;

  db.transactions.slice().reverse().forEach(function(t, idx){
    var actualIndex = db.transactions.length - 1 - idx;
    var el = document.getElementById("trans-item-" + actualIndex);
    if(el){
      setupLongPress(el, function(){
        if(confirm("Delete this transaction?")){
          db.transactions.splice(actualIndex, 1);
          saveDB();
          refreshAll();
        }
      });
    }
  });
}

function renderBranches(){
  var list = document.getElementById("branchList");
  var searchInput = document.getElementById("searchBranchInput");
  var search = searchInput ? searchInput.value.toLowerCase() : "";
  var html = "";

  var branchesToRender = db.branches;
  if(currentUser && currentUser.role === "BR"){
    branchesToRender = db.branches.filter(function(b){ return b.name === currentUser.branch; });
  }

  branchesToRender.slice().reverse().forEach(function(b, idx){
    var actualIndex = db.branches.indexOf(b);
    var searchStr = (b.name + " " + b.manager + " " + b.code + " " + b.mobile).toLowerCase();
    if(search && searchStr.indexOf(search) === -1){ return; }

    html += '<div class="item" id="branch-item-' + actualIndex + '">' +
            '<div>' +
            '<b>🏢 ' + b.name + '</b> (' + b.code + ')' +
            '<br><small>Manager: ' + b.manager + ' (' + (b.managerCode || 'N/A') + ')</small>' +
            '<br><small>Mobile: ' + b.mobile + '</small>' +
            '<br><small>Address: ' + b.address + '</small>' +
            '<br><small style="color:#777;">Added: ' + (b.joinDate || 'N/A') + '</small>' +
            '</div>' +
            '<div>' +
            '<button style="background:#dc3545;color:white;border:none;padding:6px 12px;border-radius:6px;font-size:12px;cursor:pointer;" onclick="deleteBranch(' + actualIndex + ')">Delete</button>' +
            '</div>' +
            '</div>';
  });

  if(!html){
    html = '<div class="empty">No branches found</div>';
  }
  list.innerHTML = html;
}

function deleteBranch(index){
  if(currentUser && currentUser.role !== "AD"){
    alert("Only Admin can delete branches.");
    return;
  }
  if(confirm("Are you sure you want to delete this branch?")){
    var branch = db.branches[index];
    db.branches.splice(index, 1);
    if(branch){
      db.users = db.users.filter(function(u){ return u.branch !== branch.name; });
      db.members = db.members.filter(function(m){ return m.branch !== branch.name; });
    }
    saveDB();
    refreshAll();
  }
}

function renderMembers(){
  var list = document.getElementById("memberList");
  var searchInput = document.getElementById("searchMemberInput");
  var search = searchInput ? searchInput.value.toLowerCase() : "";
  var html = "";

  var membersToRender = db.members;
  if(currentUser && currentUser.role === "BR"){
    membersToRender = db.members.filter(function(m){ return m.branch === currentUser.branch; });
  }

  membersToRender.slice().reverse().forEach(function(m, idx){
    var actualIndex = db.members.indexOf(m);
    var searchStr = (m.name + " " + m.branch + " " + m.memberId + " " + m.mobile).toLowerCase();
    if(search && searchStr.indexOf(search) === -1){ return; }

    html += '<div class="item" id="member-item-' + actualIndex + '">' +
            '<div>' +
            '<b>👤 ' + m.name + '</b> (' + m.memberId + ')' +
            '<br><small>Branch: ' + m.branch + '</small>' +
            '<br><small>Mobile: ' + m.mobile + '</small>' +
            '<br><small>Address: ' + m.address + '</small>' +
            '<br><small style="color:#777;">Join Date: ' + (m.joinDate || 'N/A') + '</small>' +
            '</div>' +
            '<div>' +
            '<button style="background:#dc3545;color:white;border:none;padding:6px 12px;border-radius:6px;font-size:12px;cursor:pointer;" onclick="deleteMember(' + actualIndex + ')">Delete</button>' +
            '</div>' +
            '</div>';
  });

  if(!html){
    html = '<div class="empty">No members found</div>';
  }
  list.innerHTML = html;
}

function deleteMember(index){
  if(confirm("Are you sure you want to delete this member?")){
    var member = db.members[index];
    db.members.splice(index, 1);
    if(member){
      db.users = db.users.filter(function(u){ return u.username !== member.memberId; });
    }
    saveDB();
    refreshAll();
  }
}

/* ===================================================== DISTRIBUTE MODULE ===================================================== */
function setupDistributePageUI(){
  var adminBranchContainer = document.getElementById("adminBranchSelectContainer");
  var branchSelect = document.getElementById("distributeBranchSelect");

  if(currentUser && currentUser.role === "AD"){
    if(adminBranchContainer) adminBranchContainer.style.display = "block";
    if(branchSelect){
      branchSelect.innerHTML = '<option value="">All Branches / Select Branch</option>';
      db.branches.forEach(function(b){
        branchSelect.innerHTML += '<option value="' + b.name + '">' + b.name + " (" + b.code + ")" + "</option>";
      });
    }
  } else {
    if(adminBranchContainer) adminBranchContainer.style.display = "none";
  }
  filterDistributeMembers();
}

function onDistributeBranchChange(){
  filterDistributeMembers();
}

function filterDistributeMembers(){
  var memberSelect = document.getElementById("distributeMember");
  if(!memberSelect) return;
  
  var selectedBranch = "";
  if(currentUser && currentUser.role === "BR"){
    selectedBranch = currentUser.branch;
  } else if(currentUser && currentUser.role === "AD"){
    var branchSelect = document.getElementById("distributeBranchSelect");
    selectedBranch = branchSelect ? branchSelect.value : "";
  }

  memberSelect.innerHTML = '<option value="">Select Member</option>';
  var membersToFilter = db.members;
  if(selectedBranch){
    membersToFilter = db.members.filter(function(m){ return m.branch === selectedBranch; });
  }

  membersToFilter.forEach(function(m){
    memberSelect.innerHTML += '<option value="' + m.name + '">' + m.name + " - " + m.memberId + " (" + m.branch + ")" + "</option>";
  });
  calculateSelectedMemberDistribution();
}

function updateDistributionAvailableBalance(){
  var interest = db.transactions.filter(function(t){ return t.type === "EMI Collect"; }).reduce(function(sum,t){ return sum + Number(t.interest || 0); }, 0);
  var otherIn = db.transactions.filter(function(t){ return t.type === "Other IN"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var otherOut = db.transactions.filter(function(t){ return t.type === "Other OUT"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var totalDistributed = db.transactions.filter(function(t){ return t.type === "Distribute"; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);

  var availableEarnings = interest + otherIn - otherOut - totalDistributed;
  var el = document.getElementById("distributionAvailableBalance");
  if(el){
    el.innerText = "₹" + availableEarnings.toLocaleString("en-IN");
  }
  return Math.max(0, availableEarnings);
}

function calculateSelectedMemberDistribution(){
  var memberName = document.getElementById("distributeMember").value;
  var amountInput = document.getElementById("distributeAmount");
  var infoBox = document.getElementById("distributionShareInfo");
  if(!memberName){
    if(amountInput) amountInput.value = "";
    if(infoBox) infoBox.style.display = "none";
    return;
  }

  var memberObj = db.members.find(function(m){ return m.name === memberName; });
  if(!memberObj){ return; }

  var branchName = memberObj.branch;
  var branchMembers = db.members.filter(function(m){ return m.branch === branchName; });
  var totalBranchMembersCount = branchMembers.length || 1;

  var interest = db.transactions.filter(function(t){ return t.type === "EMI Collect" && t.branch === branchName; }).reduce(function(sum,t){ return sum + Number(t.interest || 0); }, 0);
  var otherIn = db.transactions.filter(function(t){ return t.type === "Other IN" && t.branch === branchName; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var otherOut = db.transactions.filter(function(t){ return t.type === "Other OUT" && t.branch === branchName; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);
  var totalBranchDistributed = db.transactions.filter(function(t){ return t.type === "Distribute" && t.branch === branchName; }).reduce(function(sum,t){ return sum + Number(t.amount || 0); }, 0);

  var branchEarningsPool = Math.max(0, interest + otherIn - otherOut - totalBranchDistributed);
  var memberShare = Math.round(branchEarningsPool / totalBranchMembersCount);

  if(amountInput) amountInput.value = memberShare;
  if(infoBox){
    infoBox.style.display = "block";
    infoBox.innerHTML = "<b>Branch Pool:</b> ₹" + branchEarningsPool.toLocaleString("en-IN") + " | <b>Total Branch Members:</b> " + totalBranchMembersCount + "<br><b>Calculated Equal Share:</b> ₹" + memberShare.toLocaleString("en-IN");
  }
}

function addDistribute(){
  var memberName = document.getElementById("distributeMember").value;
  var amount = Number(document.getElementById("distributeAmount").value);
  var desc = document.getElementById("distributeDescription").value.trim() || "Monthly Profit Share";

  if(!memberName || amount <= 0){
    alert("Please select a member and ensure distribution amount is valid.");
    return;
  }

  var memberObj = db.members.find(function(m){ return m.name === memberName; });
  if(!memberObj){
    alert("Member not found.");
    return;
  }

  var availableEarnings = updateDistributionAvailableBalance();
  if(amount > availableEarnings){
    alert("Distribution amount cannot exceed available earnings pool (₹" + availableEarnings.toLocaleString("en-IN") + ")");
    return;
  }

  db.transactions.push({
    id:Date.now(),
    type:"Distribute",
    branch:memberObj.branch,
    member:memberName,
    amount:amount,
    description:desc,
    date:new Date().toLocaleString()
  });

  saveDB();
  document.getElementById("distributeAmount").value = "";
  document.getElementById("distributeDescription").value = "";
  document.getElementById("distributeMember").value = "";
  document.getElementById("distributionShareInfo").style.display = "none";
  refreshAll();
  alert("Successfully distributed ₹" + amount.toLocaleString("en-IN") + " to " + memberName);
}

function renderDistributions(){
  var list = document.getElementById("distributeList");
  var searchInput = document.getElementById("searchDistributeInput");
  var search = searchInput ? searchInput.value.toLowerCase() : "";
  var html = "";

  db.transactions.filter(function(t){ return t.type === "Distribute"; }).slice().reverse().forEach(function(t, idx){
    var searchStr = (t.member + " " + t.branch + " " + (t.description || "")).toLowerCase();
    if(search && searchStr.indexOf(search) === -1){ return; }

    html += '<div class="item">' +
            '<div>' +
            '<b>💸 Profit Distribution</b>' +
            '<br><small>Member: ' + t.member + ' (' + t.branch + ')</small>' +
            '<br><small>' + (t.description || 'Monthly Profit Share') + '</small>' +
            '<br><small style="color:#777;">' + t.date + '</small>' +
            '</div>' +
            '<div style="text-align:right;">' +
            '<b style="color:#198754;font-size:17px;">+₹' + Number(t.amount || 0).toLocaleString("en-IN") + '</b>' +
            '</div>' +
            '</div>';
  });

  if(!html){
    html = '<div class="empty">No distribution history found</div>';
  }
  list.innerHTML = html;
}

/* ===================================================== INITIALIZATION ===================================================== */
var currentUser = null;
window.onload = function(){
  var savedUser = localStorage.getItem("sirzon_current_user");
  if(savedUser){
    try{
      currentUser = JSON.parse(savedUser);
      if(currentUser){
        showApp(currentUser);
      }
    }catch(e){
      localStorage.removeItem("sirzon_current_user");
    }
  }
  updateRealTimeBadges();
};
</script>
</body>
</html>
