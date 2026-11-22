# Agent Supervision Console

A working interaction design prototype by Sijie (CJ) Yang, Principal Product Designer. How can an operator spot an agent's overreach, intervene, and see what happened afterward?

## Try the supervision loop

Open `index.html` in a browser. The console uses simulated proposals and agent activity. All decisions last for the current page session.

1. In Compliance, compare the contract renewal with the proposed export. The audit engagement covers 500 records. The export requests 118,000.
2. Approve the renewal. Pause a running agent and check that its progress holds. Both actions appear in the audit log.
3. Use **Undo last decision**. The proposal returns to the queue, and the original approval and its reversal are both visible.
4. Switch to Robot Inspection or Research Ops to explore the same controls in a different context.

Open `index.html?tour=1` for a guided review of the export. Use **Pause tour** or interact with the console to take over.

## Implementation

The interface, sample scenarios, and interaction logic live in one HTML file. It runs directly in a browser without a package install, build step, or backend. Netlify can serve the repository root as a static site.

[Design portfolio](https://uxfol.io/cjyang)
