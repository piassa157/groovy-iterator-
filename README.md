# Script Groovy

xptoFunction =  {def fooBar -> 

def getAllX = []
def getAllY = []


    if(!(X == 0 && Y == 0)){
        return false
    }

    fooBar.each{ items ->

        if(items.value == 'X'){
            getAllX.add(items)
        }

        if(items.value == 'Y'){
            getAllY.add(items)
        }

    }


    getAllX.each{ X ->
        getAllY.each{Y ->
            if(X.xpto == Y.xpto){
                /* you action here */
            }
        } 
    }

}


