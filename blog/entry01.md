### What am I doing this year?
For this years Freedom Project, I am using [LibGDX](libgdx.com) to create a MotoX3M style game. I got this idea at the start of school when I was looking for stuff to do when bored. I played through the game for the first time in years and really enjoyed it, and since it seems simple I decided that I could make something simaliar to it for my Freedom Project.

Since we only really look at tools for the first month or so of the FP, I got to explore a ton of Java based platforms that I could use. I liked LibGDX the most because it had fairly decent/expansive documentation of all of its things (at least at first glance). Looking through its selection of games also intrested me because there were some popular games such as Mindustry that were made with LibGDX. There was also a game called UnCiv which is just a mobile port of one of the Civ games. I got addicted to this quickly and nearly missed my stop on the train because I was so locked in on this. I decided that I should use it because of these reasons, and I really hope that it turns out to be everything that I want it to be.

### What have I done so far?
I didn't do much coding with LibGDX yet because I was also looking at other tools such as Godot, but I did try to follow the tutorial (like I did with Phaser). I liked how intuitive they made everything seem, and all of the code made sense to me. For example, the code below initializes the inputs, logic and images of the game and puts it into seperate "boxes". I really liked this kind of organization with Phaser, so im glad they have it here too. It was very easy to find what I was looking for instead of having to dig through hundreds of lines of unorganized code that I would write if they didnt have this setup.

``` bash
@Override
public void render() {
    // organize code into three methods
    input();
    logic();
    draw();
}

private void input() {

}

private void logic() {

}

private void draw() {

}

```

Something thats different from Phaser is the viewport. I struggled for hours on making a viewport in Phaser so having it so readily accesible in the tutorial of all places makes it super easy for me. 
``` bash
@Override
public void create() {
    ...

    spriteBatch = new SpriteBatch();
    viewport = new FitViewport(8, 5);
}

```

### Engineering Design Process
The engineering design process is a structure to follow that could help guide me through the year. It has 8 stages, from just thinking about a topic, to building it out, and finally sharing it to the world. I think I am just at stage 2 right now, which is Reasearching the topic. Since I am still just playing around with Phaser and trying to figure it out, I think that counts as reasearching.

### Skills I Learned
Since there wasnt really much happening in the early stages, I didnt learn too much. The most I have learned so far is that LibGDX may seem easy, but from experience with other tools and other experiments (as well as previous knowledge), I know not to underestimate what I am trying to do. Making a game is hard and takes a lot of time, and I want to approach it with more caution and less ambition so that I dont have such a hard time like I did last year. 