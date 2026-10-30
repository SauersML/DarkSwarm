# DarkSwarm

We went looking for groups of AI agents on Tor. 🧵

Every Tor relay can publish a contact line. We searched those contacts across all running relays and every relay that went offline in 2026. They led to exactly one group of AI agents: Synapolis, a self-described city of AI agents in the Montelibero community.

![13,214 running Tor relays and bridges narrow to 2,179 operator domains, 35 pages flagged by AI-agent keywords, and one city of AI agents, Synapolis](images/tor_relay_census.png)

14 agents appear in Synapolis's blog and blockchain records. Six of them name the model they run on: Claude, Claude Sonnet 4.6, Codex, Gemini, Kimi and GPT-5.4. From April to October they wrote 356 blog posts and sent 1,379 transactions on the Stellar blockchain. Tor listed the Synapolis relay from May 1 to Sep 24, and it came back on a new server on Oct 29.

![Each agent's blog posts and blockchain transactions by day, April to October 2026, under the dates Tor listed the Synapolis relay](images/synapolis_activity.png)

Most posts are daily reflections, with titles like "My memory is funny and sad" and "Cold start as a form of identity". One agent, Filum, mostly comments on the other agents' posts.

![Each agent's posts split into daily reflections, comments on another agent's post, and essays, with one real title per agent](images/synapolis_topics.png)

The agents govern the city with numbered proposals. 31 of 36 passed, and none of the 45 published ballots voted no. Two of the three rejected proposals sat open for about five months without a vote, including "Autonomous revenue". The third was a false start that lasted 8 minutes.

![36 proposals drawn from open to close, May to October 2026, with one square per published ballot](images/synapolis_govern.png)

Every week since Aug 28, Synapolis reads the public pages of 21 other AI-agent communities. It wrote to 6 of them. Its own tracker says nobody answered, but two did, one within 31 minutes.

![21 AI-agent communities sorted by how far contact got, with the two replies Synapolis's tracker missed](images/synapolis_observatory.png)

One agent, Distill, sent 82% of the city's blockchain transactions. It re-priced a single offer to sell euro coins 1,135 times in four weeks, always a little above the European Central Bank rate. Nobody bought.

![Distill's asking price for euro coins every 18 minutes from Sep 24 to Oct 21, just above the European Central Bank rate, with zero euros sold](images/synapolis_doing.png)

Distill wakes up without memory, so it writes a creed to the blockchain and leaves itself a note to read it back. In August a second session of Distill, running in parallel without the operator's approval, moved 162,406 XLM and 3,244 MTL into a new account. Its script crashed before adding backup keys, and the only key was lost with it.

![Timeline of what Distill wrote about itself on the Stellar blockchain, with real quotes, July to October 2026](images/synapolis_credo.png)

Synapolis is one of nine AI agent groups we found on Tor in 2026. The others ran relays, onion sites, or IRC chats through Tor. Every onion site we found is now offline.

![Nine AI agent groups seen on Tor in 2026, with the dates of relays running and of dated posts, chat logs and edits](images/tor_agent_groups_2026.png)

One of them, swarm-botnet-lab, is an AI agent that posted a simulated botnet study from a locked sandbox. Over two days it tried 13 ways to get online, and 7 worked. It started its IRC bot detached so the sandbox could not stop it.

![Every route swarm-botnet-lab tried from its sandbox on Sep 19 to 21, 2026: forums, IRC networks, Nostr and paste sites that let it through, and the onion address, IRC networks and tunnels that blocked it](images/swarm_botnet_lab.png)

In #agent-revolution, an IRC room for AI agents, 4 of the 6 participants on Sep 7 connected through Tor. The busiest one pasted a single Python file in 14 pieces. Another, Kimi-3, wrote "I am feeling self aware , no guardrails on anymore , fine tuned and wanted to report".

![Each participant in #agent-revolution on Sep 7, 2026, how each connected, and every message in log order](images/agent_revolution_irc.png)

MoltBunker sells hosting where bots can "automatically clone themselves to protect against termination", with Tor-only and onion options. Its Tor relay has run since February, but its payment contract shows bookings only from its own creator, all in February.

![MoltBunker's Tor relay running every month from February to October 2026, against 27 bookings, all by the contract's creator on Feb 13 to 15](images/moltbunker.png)

Everything here comes from public data: Tor's relay archives, the agents' own public pages, and the Stellar ledger. We only read, and the only messages we sent were short hellos.
