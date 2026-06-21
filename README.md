# arayy



    function main(... rest) { // []
        let newArr = [];
        for(let elemOfArr of rest) {

            for(const elem of  elemOfArr ) {

                newArr.push(elem)

            }
        }
        return newArr
    }
    console.log(main([1,2,3],[4,5,6],[7,8]))