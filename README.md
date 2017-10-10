        if(year==="h99") {
            var h07 = prop["h07"];
            if (!h07) h07 = 0;
            //console.log(h07);
            var h27 = prop["h27"];
            if (!h27) h27 = 0;
            //console.log(h27);

            var ritu = h27 / h07;
            if (!ritu) ritu = 0;
            if (!isFinite(ritu)) ritu = 999;

            if (ritu > 2) ritu = 2;
            ritu = ritu - 1;
            console.log(ritu);
        }else{

        }
