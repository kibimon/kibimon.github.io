#  Contributing

So, you've learned about MonStrPub and want to get involved.
Where do you begin?
Well, it depends on what you're hoping to accomplish…

+ Table of Contents
{:toc #toc}

<aside markdown="block">
It is generally expected that everyone contributing to MonStrPub be available for communication via the ActivityPub protocol.
MonStrPub is an ActivityPub extension, so you should not contribute to a MonStrPub project if you have an aversion to ActivityPub software.
</aside>

##  I want to build my own implementation.  {#impl}

That's great!
The [MonStrPub specification][MonStrPub] is organized in such a way so as to hopefully make implementing approachable to newcomers.
Here's a quick outline of the steps you will need to follow:

1.  **Implement [ActivityPub].**
    Every MonStrPub implementation must also be a conforming ActivityPub implementation, so if you haven't already done this, it's the place to start.

2.  **Implement [MonStrPub Core].**
    The requirements in this specification are fairly light and only provide the most basic functionality for sharing and interacting with mon.
    For simplicity, you can make captures, searches, and uses always fail until you are able to implement those features.
    You probably won't be able to do much with just this, but it's a place to start!

3.  **Implement other MonStrPub specifications.**
    Which specifications you choose to support is entirely up to you!
    You should think about what order of implementation makes the most sense for your project before you begin.

##  I want to contribute to Monstodon.  {#monsto}

You should contact [@kibi@glitch.social](https://glitch.social/@kibi) or [@srn@dev.glitch.social](https://dev.glitch.social/@srn), as they are the people in charge of the Monstodon implementation.
Before you do, it would be a good idea to read through the contributing guidelines [here](https://www.monstr.pub/monsto/contributing/).

##  I want to contribute to Plé-Mon.  {#ple}

You should contact [@KitRedgrave@glitch.social](https://glitch.social/@KitRedgrave), as she is the person in charge of the Plé-Mon implementation.

##  I want to extend MonStrPub with new features.  {#extend}

The MonStrPub specification is under active development, and new components are being written all the time.
Before you begin writing your own extension, you should get in touch with [@kibi@glitch.social](https://glitch.social/@kibi) to see if your idea is currently on the docket for incorporation into the spec.
If the feature you're looking for is planned, you will be encouraged to work with the KibiMon team to come up with a final specification that works for everybody.

If you're looking to develop a feature that isn't planned for incorporation into the official MonStrPub specification, that's okay!
You are free to write your own extensions to MonStrPub to suit your needs.
Be sure to assign a stable URI to your specification so that implementors can indicate their support.


[ActivityPub]:    <https://www.w3.org/TR/activitypub/>              "ActivityPub"
[MonStrPub]:      <https://www.monstr.pub/spec/monstrpub-overview/> "MonStrPub"
[MonStrPub Core]: <https://www.monstr.pub/spec/monstrpub-core/>     "MonStrPub Core"
