# Design Principles

## Headless

Output is delivered into the tools sales people already use, on a cadence
that matches how they sell. The system is decoupled from any interface of
its own, so adoption never depends on anyone changing where they work.

## Bounded autonomy

The system operates autonomously across the work it owns: interpreting
signals, enriching accounts, scoring, and routing. Every outcome it
produces stays correctable after the fact. Autonomy is granted in
proportion to how correctable the output is.

## Built for the region it serves

Source selection, classification, and calibration were designed around
the patterns of the GCC market: how companies hire, raise, and go to
market. This is built for a region default tooling overlooks.

## No manual handoffs

This is an event-driven pipeline: each stage triggers the next, and
orchestration handles every transition between systems. Nothing sits in a
queue waiting for someone to move it forward, and no one is exporting,
re-keying, or stitching two tools together by hand.

## This doesn't replace your CRM

The system feeds the source of truth a team already trusts and defers to
it entirely. Nothing here asks anyone to migrate, maintain a second
system, or reconcile duplicates. Competing with the CRM for authority
creates work.

## A signal isn't the message

A funding round or a new hire is visible to anyone with an internet
connection. The system reads that event as a cue to look closer at the
company, and the message a rep sends comes from what that closer look
turns up.

## Right-sized capability

Tooling and model selection are deliberate choices made per stage, based
on what the work genuinely demands. A frontier model is deployed where
judgment and nuance carry the outcome. Lighter models and deterministic
tooling handle work that is well defined. Matching capability to the
demand of the task keeps performance high at every stage and cost
proportionate to the value being produced.
