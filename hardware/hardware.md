# Hardware

What hardware do we want for these AI Experiments. We have two available machines:

1.  The Intel NUC with graphics card for LLM
1.  Raspberry PI with the AI hat for other AI Experiments

One of the problems with the raspberry pi AI HAT is that it uses the PCI slot, meaning
you lose the option of using an NVME slot too. This page investigates solutions to
that problem.

So, the AI HAT is just and NVMe plugin thingy it seems, so we can get a dual NVME and use
that to run them both: https://52pi.com/products/raspberry-pi-5-b12-double-fpc-pcie-hat-1

I have a 500G NVMe that I can use for this. So things we need:

1.  Raspberry Pi 5 8Gb
2.  Stock Cooler
3.  MicroSD Card
4.  https://pineboards.io/blogs/news/introducing-the-ai-bundle-hailo-8l

The pineboard combines the AI accelerator chip and and NVME slot. That seems like a good way
forward.