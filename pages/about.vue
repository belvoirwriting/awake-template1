<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="About Us"
      subtitle="Helping you find your own voice as a writer since 2018"
      image="/uploads/about-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
          
         
          <p>
           If you enjoy writing, or feel like giving it a go, you will be welcomed with great
encouragement by like-minded people
There will also be inspiration in the form of occasional guest novelists, poets, song writers
and journalists.
          </p>

          <h3>Inspiring meetings</h3>
          <p>
         We meet on the second Tuesday of every month at St. Mary's Church in Bottesford, but have been using Google Meet during the current restrictions. There's an optional theme or prompt for each meeting to help kick start your next piece.
          </p>
          <h3>Variations on a theme</h3><p>
          We’ve had fun playing with the different themes, diverging from them in different ways or discarding them altogether to present works in progress. We've shared a variety of stories, poems, memoirs, novel chapters, blog posts and more. 
</p>
<ul>
Our previous themes have included:
<li>Tale with a twist ending</li>
<li>Beneath the surface</li>
<li>An unexpected detour</li>
<li>Your future self</li>
<li>A step too far</li>
<li>Spotlight on a character</li>
<li>The gift</li>
</ul>
<p>
</p>
<p>
How you respond to the month’s theme is up to you, because, most of all, the group is about enjoying and encouraging writing.
</p>
<h3>Writers from across the Vale of Belvoir</h3><p>
Most of our writers live in or near the Vale of Belvoir, but distance has been no object under lockdown. We’ve switched to video meetings and settled on Google Meet after considering Zoom, Skype and others for our calls, allowing everyone to join in, wherever they are.
</p><p>
We look forward to meeting again in person as restrictions are lifted further and when it becomes safer to do so.
</p>
              
        </div>

     
      </template>

      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
