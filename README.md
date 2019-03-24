# GDC2019_Public
This is the public repository for my GDC 2019 presentation, entitled "Breaking Down Barriers - An Introduction To GPU Synchronization". The talk was given as part of the Advanced Graphics Techniques tutorial session.

The basic purpose of this talk is to fill in some of the gaps that you might have around how barriers actually work on typically GPUs, and also explain why they're needed in the first place. In that regard it's intended to more accessible to people that don't have a lot of low-level GPU programming experience, or are new to the "explicit" APIs such as D3D12 and Vulkan. The slides here include full speaker notes that are intended to roughly match what I said at the actual talk, so that you can hopefully get the full experience even if you didn't attend.

Here's the full description from the GDC schedule page:

*The recent wave of "explicit" graphics APIs such as Vulkan and D3D12 require that programmers make use of barriers, events, fences, and other GPU-side synchronization primitives in order to obtain correct results. For programmers new to GPU programming or who are used to other APIs that don't require barriers, it's not at all obvious why barriers are needed or what they're actually doing under the hood. This presentation aims to remove much of the mystery around barriers by explaining how they work on modern PC and console GPU architectures.*

*Attendees will gain a better understanding of why barriers are necessary, and also what implications they have on GPU utilization and performance. This talk will also explain how barriers and synchronization tie into more complex topics such as submitting commands to multiple hardware queues (AKA Async Compute).*
