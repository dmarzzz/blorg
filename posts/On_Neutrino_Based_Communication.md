[category]: <> (science)
[date]: <> (2025/10/26)
[title]: <> (On Neutrino Based Communication)

In *Understanding Media The Extensions of Man*, the Canadian philosopher Marshal Mcluhan eloquently stated, “During the mechanical ages we had extended our bodies in space. Today, after more than a century of electric technology, we have extended our central nervous system itself in a global embrace, abolishing both space and time as far as our planet is concerned.” I often think about this statement and wonder: what technology changes the last bit, from "our planet" to "our galaxy"? Towards this end, I explore an futuristic communication medium, neutrinos.


## TL;DR
- Neutrinos are near massless particles that interact extremely weakly with matter, trillions pass through your hand every second.
- Neutrinos are interesting for long range communication due to their ability to travel at near the speed of light, in a straight line, and encounter very little obstacles.
- Neutrinos are also interesting for censorship resistant communication since a censor would need to encase the transmitter in a 360 degree wall of netrino blocking material.
- Detection of Neutrinos is extremely hard, but possible. In 1955 Project Poltregeist detected 3 neutrinos per hour. Today the IceCube Neutrino Observatory detects 10 neutrinos per hour.
- Researchers in 2024 were able to transmit the word "neutrino" over 1km at 0.1 bits/s with an error rate of 1%.
- Sending an unrealistic 1-bit Buy "B" or Sell "S" signal over a neutrino from New York to Tokyo would take over 1s, meaning we need 100x improvement in neutrino detection capabilities to be interesting.

---

## Neutrinos

*I'll start out by prefacing that the use of neutrinos for communication is both extremely exotic, as well as extremely not feasible for anything like permissionless finance anytime soon. Nonethless, that shouldn't stop us from looking towards the future, and in true human ingenuity, a few people have already expored the topic!*

[Neutrinos](https://en.wikipedia.org/wiki/Neutrino) are the ghosts in the [standard model](https://en.wikipedia.org/wiki/Standard_Model) of elementary particles. The standard, and [somewhat apocryphal example](https://physics.stackexchange.com/questions/532708/what-is-the-evidence-for-billions-of-neutrinos-pass-through-your-body-every-sec), given with every introduction to neutrinos is that "[about 100 trillion neutrinos pass through our bodies every second](https://www.smithsonianmag.com/science-nature/looking-for-neutrinos-natures-ghost-particles-64200742/)". Neutrinos exhibit this interesting property because they are relatively massless. In fact, they are so massless that the [2015 Nobel Prize in Physics](https://www.nature.com/articles/nphys3543) was awarded to [Takaaki Kajita](nobelprize.org/nobel_prizes/physics/laureates/2015/kajita-facts.html) and [Arthur B. McDonald](https://www.nobelprize.org/prizes/physics/2015/mcdonald/facts/) for the most conclusive experimental evidence that they had any mass at all! The other contributing factor is that they only interact via the [weak force](https://en.wikipedia.org/wiki/Weak_interaction).

Additionally they travel at near the speed of light, a property that SETI magainze Cosmic Search Vol. 1 says, ["the possibilities of using neutrinos as the vehicle for interstellar communication should be carefully explored... since most other communicating civilizations would be far more advanced than our own, it is an interesting exercise to examine alternative means by which interstellar communication may have evolved."](http://www.bigear.org/vol1no3/neutrino.htm)

![Table of Elementary Particles](https://hackmd.io/_uploads/BJadF-R6xe.png)


### How Do We Detect Neutrinos?

Already you may see where my train of thought goes, that because of this ability, or lack of ability, to interact with matter, this makes them in principle extremely attractive for censorship resistant communications. If you were to harness such capability, then someone would need to place a 360 degree ball of neutrino blocking material all around the transmitter for you get censored. This means a critical message from one side of the planet could be communicated through the center!

The very natural next question is then, if they pass through everything, then how could you possibly detect them? Well the answer, atleast right now, is at ***very low  rates***. At it's core all detection methods rely on the interaction of neutrinos with other particles that then themselves emit another particle which is more easily detectable.

#### The First Detection
After being theorized in 1930 by Wolfgang Pauli, the earliest experiments to detect neutrinos were by [Clyde L. Cowan and Frederick Reines](https://icecube.wisc.edu/neutrino-history/1956/01/1956-first-discovery-of-the-neutrino-by-an-experiment/). They "[hypothesized that a neutrino might interact with a proton to produce a neutron and a positron. The positron would in turn interact with any nearby electron, annihilating both itself and the electron and producing two detectable gamma rays. The probability of such an interaction is extremely low (one in one trillion trillion), so a large neutrino generator and a large source of protons would be necessary.](https://www.lanl.gov/media/publications/national-security-science/0325-project-poltergeist)".

Their aptly named Project Poltergeist was initially approved to use [the neutrino flux from a 20-kiloton nuclear bomb test](https://www.lanl.gov/media/publications/national-security-science/0325-project-poltergeist) at Los Alamos, comparable to that dropped on Hiroshima, but after some dissuasion, they instead turned to a nuclear reactor in South Carolina. The reactor produced a steady stream of the then theoretical neutrinos, which they directed toward a 200-liter water tank laced with 40 kg of dissolved cadmium. When antineutrinos struck protons in the water, they produced positrons and neutrons. The positrons’ annihilation yielded two gamma rays, and moments later the neutrons were absorbed by cadmium, releasing a third. And "after months of data collection, they had accumulated data on about three neutrinos per hour in their detector."


#### Cosmic Scale Detection

Since 1955, an entire observatory devoted to the detection of neutrinos has been built. The aso aptly named [IceCube Neutrino Observatory](https://icecube.wisc.edu/) is located in the South Pole and uses a cubic kilometer of Antarctic ice instrumented with photomultiplier tubes (optical sensors) to detect Cherenkov light from secondary charged particles created when neutrinos interact in the ice. IceCube is designed to detect higher energy neutrinos from cosmic events than those that are ommitted from terrestial nuclear reactions. Because of this, they detect, "275 million cosmic rays" a day, and "275 atmospheric neutrinos daily and about 100,000 per year".

![image](https://hackmd.io/_uploads/HknAWz0ple.png)
*"The IceCube Neutrino Observatory encompasses a cubic kilometer of ice below the surface near Amundsen-Scott South Pole Station. This illustration simulates the interaction of a neutrino with a molecule of ice. Photo Credit: IceCube Collaboration/NSF"*

IceCube turns a cubic kilometer of ice into one of the largest telescopes on Earth—not by observing light directly from the stars, but by catching the faint blue glow produced when neutrinos finally do interact with matter referred to as [Cherenkov radiation](https://en.wikipedia.org/wiki/Cherenkov_radiation). When a high-energy neutrino collides with a molecule of ice, it transfers its energy to a secondary charged particle (often a muon or electron). That secondary particle then moves faster than light can travel through ice, generating a cone of Cherenkov radiation—a bluish flash similar to an optical sonic boom.

Over 5,000 digital optical modules buried deep in the ice register the timing and intensity of these "Cherenkov photons". From the pattern and delay of signals across the grid, IceCube reconstructs the incoming particle’s direction and energy, effectively tracing the neutrino’s origin back to its cosmic source. Though the neutrinos themselves remain invisible, their ghostly footprints of light allow scientists to map violent astrophysical events—supernovae, blazars, and black holes—from across the universe.

![image](https://hackmd.io/_uploads/HkJxImA6ll.png)


### How Can We Use Neutrinos for Communication

Numerous scientific endeavors have equipped us with all the tools we need to communicate with neutrinos: the ability to generate neutrino beams, the ability to detect them, and good old signal theory which enables us to encode a signal.

And recently a team of scientist did exactly that. In [a paper published in 2024](https://arxiv.org/pdf/1203.2847), they report "on the performance of a low-rate communications link established using the NuMI beam line and the MINERvA detector at Fermilab. The link achieved a decoded data rate of 0.1 bits/sec with a bit error rate of 1% over a distance of 1.035 km that included 240m of earth. This demonstration illustrates the feasibility of using neutrino beams to provide a low-rate communications link, independent of any existing electromagnetic communications infrastructure. However, given the limited range, low data rate, and extreme technologies required to achieve this goal, significant improvements in neutrino beams and detectors are required for “practical” application."

The methodology of their approach is not so different to those of Clyde Cowan and Frederick Reines, except scientists now have a consistent generator of neutrinos called the Neutrino beam at the Main Injector (NuMI) at Fermilabs. To generate this beam of neutrinos, protons are sent down a long tunnel where they collide with a graphite target, creating a shower of unstable particles such as pions and kaons. These particles are then guided by strong magnetic fields into a long decay tunnel, where they naturally decay into muons and neutrinos. The muons are absorbed by thick shielding material, while the neutrinos—almost entirely unaffected by matter—continue straight through the Earth toward detectors located far underground. This entire process effectively transforms the accelerator into a “neutrino beam generator,” capable of sending a focused stream of neutrinos through solid rock.

![Screenshot 2025-10-16 at 5.05.31 PM](https://hackmd.io/_uploads/SyO8D7Cage.png)

Now that we can reliably emit and detect in this environment, the next step is to encode a message. The NuMI beam was configured to emit timed bursts of neutrinos to enable one of the simplest forms of signal encoding, known in classical communication theory as [on–off keying](https://en.wikipedia.org/wiki/On%E2%80%93off_keying). Each burst of neutrinos produced by the accelerator is treated as a digital “on” signal, while pauses between bursts represent “off", enabling a binary code. And at the end of this process, the first message ever sent over neutrinos was decoded, "neutrino".

A roughly accurate to the paper image generated by Google nano banana illustrating the neutrino beam and muon detectors is shown below.
![image](https://hackmd.io/_uploads/rJbN4Dcage.png)



### When Would We Use Neutrino Based Communication


The [2024 paper](https://arxiv.org/pdf/1203.2847) referenced above established the state of the art at 0.1 bit/second through the use of neutrinos. Although the experiment achieved a bit error rate of about 1%, only 15 of 3,454 frames were successfully synchronized, corresponding to a packet-loss-equivalent rate of roughly 99.6%. This illustrates how extremely sparse detections constrain the practical bandwidth of neutrino communication systems. But optimistically, the results are way better than this [XKCD cartoon](https://xkcd.com/3017/) from many years ago. [Recent improvements to detection techniques have also emerged](https://physics.yale.edu/news/moore-group-develops-innovative-technique-detect-elusive-particles)!

![image](https://hackmd.io/_uploads/Ske_w-Raxx.png)

So communication via neuntrino is fast, but very low bandwidth. Ignoring bandwidth constraints, we can use some basic geometry to understand when it would be faster.

Let's forget the Earth is an irregularly shaped ellipsoid for a second. On a spherical Earth, surface signals (like fiber routes) follow a curved arc around the planet, while a neutrino beam could travel in a straight line through it. That straight line, a chord, is always shorter than the curved path along the surface. For short distances the difference is tiny, but for long distances, especially through the Earth’s core, the shortcut becomes dramatic.

If we only consider how long light (or a neutrino) takes to travel that path, ignoring hardware delays, the neutrino beam effectively travels at the speed of light in a vacuum $c$. By contrast, signals in fiber travel slower, about $c / 1.468 ≈ 0.68 c$, because light moves more slowly in glass. Even for equal path lengths, neutrinos would arrive sooner than fiber, and combined with their shorter route, the difference grows further.

We can use the following formulas to create a table to illustrate the advantage of neutrino based communication ignoring bandwidth.

$$
\text{Surface Arc Length: }s = R \theta \
$$

$$
\text{Neutrino Chord Length: } d = 2R \sin\left(\frac{\theta}{2}\right) \
$$

$$
\text{Neutrino Propagation time: } T_\text{neutrino} = \frac{d}{c} \
$$
$$
\text{Fiber Propagation Time: } T_\text{fiber} = \frac{s}{c/n} = \frac{n s}{c} \
$$
$$
\text{Propagation Ratio} = \frac{T_\text{neutrino}}{T_\text{fiber}} = \frac{2 \sin(\theta/2)}{n \theta}
$$


where:
	• R = `6,371 km` (Earth radius)
	• n = `1.468` (refractive index of fiber)
	•	$\theta$ is the central angle between two points on Earth (in radians)

| Scenario | Surface Arc (km) | Neutrino Chord (km) | Path Saving | Ideal Neutrino vs Fiber |
|-----------|------------------|---------------------|--------------|--------------------------|
| City-scale (500 km) | 500 | 500 | 0.0% shorter | 31.9% faster |
| Regional (1,000 km) | 1,000 | 999 | 0.1% shorter | 32.0% faster |
| US coast-to-coast (~4,500 km) | 4,500 | 4,407 | 2.1% shorter | 33.3% faster |
| China width (~5,500 km) | 5,500 | 5,331 | 3.1% shorter | 34.0% faster |
| Antipodes (half Earth) | 20,015 | 12,742 | 36.3% shorter | 56.6% faster |

***But let's get a bit more realistic, since we totally ignored bandwidth above.***

Even though neutrino propagation is faster in theory, bandwidth completely dominates latency in practice.
At 0.1 bit per second (the Fermilab result), it takes 10 seconds to send a single bit.
Let’s compare that to modern fiber transmission between New York (NYSE) and Tokyo, which can carry gigabits per second with a one-way latency of roughly 70–120 ms.

Suppose we only need to send a minimal trading signal: either “Buy” or “Sell.” 

Even with such a tiny message, the difference is dramatic:

| Message Type | Bits Sent | Neutrino TX Time (0.1 bps) | Neutrino Propagation | Total Neutrino Time | Fiber Propagation | Fiber (Internet) Total |
|---------------|-----------:|---------------------------:|----------------------:|--------------------:|------------------:|-----------------------:|
| 1-bit signal (“Buy” / “Sell”) | 1 | 10.0 s | 0.032 s | **≈10.03 s** | 0.053 s | **≈0.07–0.12 s** |
| 8-bit signal (ASCII ‘B’ / ‘S’) | 8 | 80.0 s | 0.032 s | **≈80.03 s** | 0.053 s | **≈0.07–0.12 s** |
| 32-bit redundant packet (error-protected) | 32 | 320.0 s | 0.032 s | **≈320.03 s** | 0.053 s | **≈0.07–0.12 s** |

So while a neutrino message would arrive milliseconds earlier if both were transmitted simultaneously, it would take seconds or even minutes just to get a simple "Buy" or "Sell" trading signal reliabily.


## Toward Neutrino Net
According to available government sources, which should absolutely be double-checked, building the [NuMI beam line cost roughly $136 million](https://history.fnal.gov/historical/accelerator/numi_glad_tidings.html), and the [MINERvA detector another $4–6 million with installation and contingency](https://minerva.fnal.gov/wp-content/uploads/2016/02/proposal.pdf). Of course none of this accounts for decades of maintenance, operation, or inflation. Conservatively, scaling to a modern equivalent puts the combined cost closer to $2 billion.

If detection efficiency improved by even two to three orders of magnitude, boosting throughput from 0.1 bit/s to roughly 10–100 bit/s, a single neutrino beam could transmit basic trading signals in real time, cutting straight through the planet faster than any fiber route could circle it. For high-frequency trading firms, which already spend millions to shave microseconds, such a latency advantage would be priceless.

Thus the first domino to fall that would trigger the ultimate arrival of a neutrino based communicaiton network ("neutrino net") is simply one successful trading signal sent over neutrinos. From there, each HFT would fund their own version, rapidly expanding the state of the art and total bandwidth available. Call your favorite HFT today and tell them about neutrinos!


![image](https://hackmd.io/_uploads/HyadwrmCxe.png)

