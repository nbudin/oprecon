# Operation: RECON trailer

![Screen Shot 2022-02-20 at 11 54 51 AM](https://user-images.githubusercontent.com/7477/154861676-b16c3d62-e438-403b-a2a3-817eaf6fa862.png)

This is the trailer for _Operation: RECON_, an unfinished game that I worked on along with Randy Dykstra in the mid-90s.
Unfortunately I've lost the original source code, but I've reconstructed it from the public release of the trailer.

This version is set up to compile via [agikit](https://github.com/nbudin/agikit), an open source AGI development
toolchain. I'm using this project in part to help with developing agikit, in order to have a project to experience
the development lifecycle with.

The initial checkin is an agikit-compatible version of the decompiled assets, cleaned up a bit by hand. I'm planning
to update this project as agikit develops, upgrading it to AGIv3 from the original v2 source code, and using it to
test additional agikit development work.

## Compiling and running this project

To compile the _Operation: RECON_ trailer using command line tools:

```bash
npm install -g @agikit/cli
agikit build .
```

This will output a built version of the game into the `build` subdirectory, which you can run via ScummVM, NAGI, or any
other AGI engine.

To compile and run this project using Visual Studio Code, install
[the agikit-vscode extension](https://marketplace.visualstudio.com/items?itemName=nbudin.agikit-vscode) and open this
project as a workspace. There should be a "Run AGI project with ScummVM" option in the "Run and Debug" sidebar.

## What happened to Operation: RECON?

While I was working on the original _Operation: RECON_ project, it got to the point where we had the first few rooms
working, but I no longer have the source code for that version of that version of the game. Randy had brought in
Leigh Ann Frey to work on the game with us, and I had started working on a version control system called AGIVS so that
we could simultaneously be working on the project via the Internet. It never really totally got to the point where it
worked, and I'm not sure that the other devs would have been happy using a hacked-up version control system that I
wrote in Perl in the first place.

In addition to that, due to a variety of factors, I ended up stepping away from the project without really informing
my collaborators. A lot of that was because I was in the process of applying to college and then going to college, and
that took up quite a lot of my free time.

It also became increasingly clear to me that Randy and I weren't going to see eye-to-eye on some non-project-related,
but important issues. In particular, Randy was a devout Christian and would occasionally send messages to the AGI
message board evangelizing. I'm Jewish, and I felt uncomfortable that a person I was strongly associated with was
doing this. The two of us talked about it over email, and it didn't ruin our relationship, but it was clear that we
were coming at life from extremely different points of view.

There was also an incident where my mom went into my email inbox and, due to some unfortunate truncation on the part of
Eudora, "Randy Dykstra" looked like "Randy Dyk..." and she came away with an extremely wrong impression of what sort of
emails I was exchanging with strangers on the Internet. (Which was especially ironic considering who Randy actually
was!) I tried to explain to her, but she made it clear that she wasn't happy that I was emailing strangers on the
Internet regardless.

All that being said, whatever my reasons for stepping away at the time, I certainly should have spoken with Randy and
Leigh Ann about doing so. I wish I had, and I regret it now. Randy, Leigh Ann, if you're coming across this, I'm sorry.

_- Nat Budin, February 2022_
