<script lang="ts">
  import ProjectItem from "./ProjectItem.svelte";
</script>

<section id="projects">
  <hr class="divideLine" />
  <ul class="projectsWrap">
    <ProjectItem
      title={"Hook you"}
      description={"Game where you playing as some kind of fox with hook that is have to go to the next room. Game is full of interesting and aesthetic details.<a class='link' href='https://relisqu.itch.io/hookyou'>check it out</a>"}
      video={{
        width: "352",
        height: "334",
        src: "src/static/projects/hookYou.mp4",
      }}
    />
    <ProjectItem
      title={"BringSnowball"}
      description={"Here you are a litsle mouse whose mission is to bring snow ball to the specific spot going through different obstacles. But snowball is melting, so hurry up!"}
      video={{
        width: "320",
        height: "172",
        src: "src/static/projects/mouse.mp4",
      }}
    />
    <ProjectItem
      title={"Space Ping Pong"}
      description={"Classic very popular ping pong game where you have to move platform, to bounce the ball that breaks the bricks. Be careful and don't break lost your ball :)"}
      video={{
        width: "362",
        height: "300",
        src: "src/static/projects/pingPong.mp4",
      }}
    />
    <ProjectItem
      title={"Anlaut"}
      description={"Game which is some kind of add-on over classic flappy bird game. You could take some more species with yourself that gives you extralives and have unique properties such as blasters to shout the enemies. Mission is to go as far as you can or go till the end of the level."}
      video={{
        width: "198",
        height: "358",
        src: "src/static/projects/anlaut.mp4",
      }}
    />
  </ul>
</section>
