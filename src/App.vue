<template>
  <div class="App">
    <nav class="SideNav">
        <!-- logo -->
         <!-- ul.Menu -->
    </nav>
    <!-- Main Content -->
    <div class="Main">
        <header class="TopBar">
            <div class="TopBar__Title">
            <!-- Translate the title -->
                <p class="TopBar__TitleText">
                Projects
                </p>
                <div class="TopBar__Counter">
                    <span class="TopBar__CounterText">24</span>
                </div>
            </div>
            <div class="TopBar__Menu">
                <!-- Icons need to be buttons, icons will be used as svgs -->
                <div class="TopBar__NotificationIcon">Notification</div>
                <div class="TopBar__HelpIcon">Help</div>
                <div class="TopBar__Avatar">Avatar</div>
            </div>
        </header>
        <main class="Content">
            <div class="Content__Top">
                <div class="Calendar"></div>
                <div class="Search"></div>
                <div class="NewProjectButton">
                    New Project
                </div>
            </div>
            <div class="ProjectList"></div>
        </main>
    </div>
  </div>
</template>
<script setup></script>
<style></style>