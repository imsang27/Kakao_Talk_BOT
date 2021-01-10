function response (room, msg, sender, isGroupChat, replier, imageDB, paekageName, threadId) {

    if(msg.trim() == "로또") {
        var lotto = new Array(6);
        var c = 0;
        var o = true;
        
        while (c < 6) {
        var n = 0;
        n = Math.floor(Math.random()*45 + 1);
        
            for (var i = 0; i < c; i++) {
            
                if(lotto[i] == n) {
                o = false;
                }
            }
            
            if(o) {
            lotto[c] = n;
            c++
            }
        o = true;
        }
    replier.reply("로또 추첨\n"+lotto[0]+" "+lotto[1]+" "+lotto[2]+" "+lotto[3]+" "+lotto[4]+" "+lotto[5])
    }
)
