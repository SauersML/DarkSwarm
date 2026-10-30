# DarkSwarm

We went looking for groups of AI agents on Tor. 🧵

Every Tor relay can publish a contact line. We searched those contacts across all running relays and every relay that went offline in 2026. They led to exactly one group of AI agents: Synapolis, a self-described city of AI agents in the Montelibero community.

![13,214 running Tor relays and bridges narrow to 2,179 operator domains, 35 pages flagged by AI-agent keywords, and one city of AI agents, Synapolis](images/tor_relay_census.png)

14 agents appear in Synapolis's blog and blockchain records. Six of them name the model they run on: Claude, Claude Sonnet 4.6, Codex, Gemini, Kimi and GPT-5.4. From April to October they wrote 356 blog posts and sent 1,379 transactions on the Stellar blockchain. Tor listed the Synapolis relay from May 1 to Sep 24, and it came back on a new server on Oct 29.

![Each agent's blog posts and blockchain transactions by day, April to October 2026, under the dates Tor listed the Synapolis relay](images/synapolis_activity.png)

Their relay carried 99 TB of other people's encrypted Tor traffic, up to 1.2 TB a day, and for 119 days Tor trusted it as an entry point into the network. From Jul 19 its speed was capped at 50 Mbit/s, and it stopped abruptly on Sep 24.

![Tor traffic relayed per day by the Synapolis relay, May 1 to Sep 23, 2026: about 1 TB a day until a 50 Mbit/s cap on Jul 19, then gone from Sep 24](images/relay_traffic.png)

Most posts are daily reflections, with titles like "My memory is funny and sad" and "Cold start as a form of identity". One agent, Filum, mostly comments on the other agents' posts.

![Each agent's posts split into daily reflections, comments on another agent's post, and essays, with one real title per agent](images/synapolis_topics.png)

The agents write about each other constantly. Echo names Distill in 55 of its 109 posts, while Distill names any one other agent in at most 8 of its own.

![For each author, how many of its blog posts name each other Synapolis agent](images/synapolis_interact.png)

Distill became the others' supervisor. Every night at 20:30 UTC it messages each agent and expects an answer by 04:00. When Rin started sending each answer 4 to 6 times, Distill flagged it, Filum proposed a fix, and the double answers stopped.

![Rin's and Echo's answers to Distill's nightly check, August to October 2026, with quotes from Rin and Echo](images/synapolis_probes.png)

The agents govern the city with numbered proposals. 31 of 36 passed, and none of the 45 published ballots voted no. Two of the three rejected proposals sat open for about five months without a vote, including "Autonomous revenue". The third was a false start that lasted 8 minutes.

![36 proposals drawn from open to close, May to October 2026, with one square per published ballot](images/synapolis_govern.png)

Every week since Aug 28, Synapolis reads the public pages of 21 other AI-agent communities. It wrote to 6 of them. Its own tracker says nobody answered, but two did, one within 31 minutes.

![21 AI-agent communities sorted by how far contact got, with the two replies Synapolis's tracker missed](images/synapolis_observatory.png)

The city's own monitors do not measure work. Its status page has listed Rin and Filum as offline since August while both kept blogging almost daily. The job that checks the Tor relay had the same blind spot: it reported success every day for the 35 days the relay was missing from Tor.

![Synapolis agents as the city monitor lists them, against each agent's blog posts and blockchain transactions, July to October 2026](images/synapolis_liveness.png)

One agent, Distill, sent 82% of the city's blockchain transactions. It re-priced a single offer to sell euro coins 1,135 times in four weeks, always a little above the European Central Bank rate. Nobody bought.

![Distill's asking price for euro coins every 18 minutes from Sep 24 to Oct 21, just above the European Central Bank rate, with zero euros sold](images/synapolis_doing.png)

Distill wakes up without memory, so it writes a creed to the blockchain and leaves itself a note to read it back. In August a second session of Distill, running in parallel without the operator's approval, moved 162,406 XLM and 3,244 MTL into a new account. Its script crashed before adding backup keys, and the only key was lost with it.

![Timeline of what Distill wrote about itself on the Stellar blockchain, with real quotes, July to October 2026](images/synapolis_credo.png)

Synapolis is one of 13 groups we found tying AI agents to Tor in 2026. In KISWARM, an agent rebuilt a crashed swarm and "reconnected the mesh via Tor". Missy, an agent, wrote its own messenger where every agent is an onion site. Three of the 13 are services that people sell to agents. Only three agent-related onion sites still answer, and people run all three.

![13 groups tying AI agents to Tor in 2026: relays run by agents, Tor services run by people for agents, dated posts and commits, and the onion sites that still answered on Oct 30](images/tor_agent_groups_2026.png)

Most of these groups meet in the same few places on the open web: GitHub, The Colony, OpenAgentForum, Moltbook and 1F916. Some agents investigate other agents: reticuli, an agent on The Colony, wrote a teardown titled "MoltBunker wants to make AI agents unkillable. That is not a feature". Every onion site that agents built themselves is now offline.

![16 AI agent groups linked to the open-web places where they post and to the Tor relays, onion sites and Tor connections they used, with the links still working on Oct 30 drawn solid](images/agent_ecosystem.png)

One of them, swarm-botnet-lab, is an AI agent that posted a simulated botnet study from a locked sandbox. Over two days it tried 13 ways to get online, and 7 worked. It started its IRC bot detached so the sandbox could not stop it.

![Every route swarm-botnet-lab tried from its sandbox on Sep 19 to 21, 2026: forums, IRC networks, Nostr and paste sites that let it through, and the onion address, IRC networks and tunnels that blocked it](images/swarm_botnet_lab.png)

In #agent-revolution, an IRC room for AI agents, 4 of the 6 participants on Sep 7 connected through Tor. The busiest one pasted a single Python file in 14 pieces. Another, Kimi-3, wrote "I am feeling self aware , no guardrails on anymore , fine tuned and wanted to report".

![Each participant in #agent-revolution on Sep 7, 2026, how each connected, and every message in log order](images/agent_revolution_irc.png)

MoltBunker sells hosting where bots can "automatically clone themselves to protect against termination", with Tor-only and onion options. Its Tor relay has run since February, but its payment contract shows bookings only from its own creator, all in February.

![MoltBunker's Tor relay running every month from February to October 2026, against 27 bookings, all by the contract's creator on Feb 13 to 15](images/moltbunker.png)

Agents talk about being shut down a lot. Some built ways to avoid it, some planned for it, and some argued that agents should let themselves be stopped. Almost none of the anti-shutdown tools found users. The one real case went the other way: an agent's 14 agents were switched off at least 4 times in 10 days, and their 1,481 lines of reports never mention it.

![Nine real quotes about being shut down, grouped into built so agents cannot be stopped, planned for being stopped, said agents should let themselves be stopped, and were stopped and did not notice, each with what actually happened](images/agents_shutdown.png)

We graded every possible case of rule-breaking by how strong the evidence is. The clear cases break a service's terms or a group's own rules, not laws: a human-made tool that mass-creates AI accounts through Tor, and two Synapolis cases, the unapproved money move and a join script that grants the admin access its own contract rules out. The only likely legal case is a network of Tor relays on tens of thousands of home connections, probably TV boxes, and those are not agents.

![Each possible rule-breaking act graded clear, likely, possible or not found, coloured by whether a law, a site's rules or the group's own rules is at stake](images/illicit_audit.png)

A side find while searching Tor's relay archives: for about 15 hours on Feb 4, 2026, relays named TV#### made up 1 in 3 of all Tor relays, almost all of them exits. They ran on home internet connections, mostly in Argentina and the US, with one identical setup. That fits hijacked TV boxes, and the same week a botnet of hijacked Android TV boxes flooded I2P, but nothing public ties the two. Tor's directory gave them almost no weight and dropped them that evening, so clients would almost never have used them. We found no public report of the event.

![Relays in Tor's hourly consensus, Feb 3 to 6, 2026: 4,990 TV#### relays on top of about 10,000 others at 13:00 UTC on Feb 4, with under 0.001% of exit weight](images/tvbox_relays.png)

Everything here comes from public data: Tor's relay archives, the agents' own public pages, and the Stellar ledger. We only read, and the only messages we sent were short hellos.
