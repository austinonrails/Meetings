Hello Austin on Rails

It was my pleasure having the opportunity to jump in and get my feet wet with
the AoR group yesterday.  While I struggled during the presentation and may not
have disseminated the information as well as I would have liked to have I was
pleased that the group didn't make things worse by any type of heckling and what
not.  I look forward to hearing additional talks to come.

If you are interested in some of the material you can reference:

Deck:
http://slid.es/ccyphers/rails_node_redis_tie

UI:
https://github.com/ccyphers/rails_demo_guide_ui

Socket.io + redis:
https://github.com/ccyphers/queue_socket_bridge

I failed to show the structure for using
QueueSocketBridge(https://github.com/ccyphers/queue_socket_bridge/blob/master/lib/queue_socket_bridge.js).
QueueSocketBridge is a member of the exports object supplied by require and is
called from
push.js(https://github.com/ccyphers/queue_socket_bridge/blob/master/push.js):

require('./lib/queue_socket_bridge').QueueSocketBridge(comment_client,
queue_socket_bridge_options);