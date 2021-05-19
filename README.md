# PokerStarsTextToJson

A txt to json parser for poker stars hand history files.

{
    players: [
      'fengarib',
      'dkaz99',
      'Acidsensei',
      'AAATATATA',
      'Cherryballer',
      'Mitsunari666'
    ],
    intro: [ [Object], [Object], [Object], [Object], [Object], [Object] ],
    preflop: { Raise: [], Reraise: [] },
    flop: undefined,
    turn: undefined,
    river: undefined,
    showDown: undefined,
    summary: [ [Object], [Object], [Object], [Object], [Object], [Object] ]
  },
  {
    players: [
      'fengarib',
      'dkaz99',
      'Acidsensei',
      'AAATATATA',
      'Cherryballer',
      'Mitsunari666'
    ],
    intro: [ [Object], [Object], [Object], [Object], [Object], [Object] ],
    preflop: { Raise: [Array], Reraise: [] },
    flop: [
      '*** FLOP *** [3h 7d 9d]\r',
      'fengarib: check \r',
      'Acidsensei: ποντάρει 250\r',
      'Cherryballer: fold \r',
      'fengarib: fold \r',
      'Το ποντάρισμα στο οποίο δεν έγινε call (250) επιστράφηκε στον Acidsensei\r',
      'Acidsensei μάζεψε 511 από  pot\r',
      'Acidsensei: δε δείχνει το χέρι του \r'
    ],
    turn: undefined,
    river: undefined,
    showDown: undefined,
    summary: [ [Object], [Object], [Object], [Object], [Object], [Object] ]
  },
