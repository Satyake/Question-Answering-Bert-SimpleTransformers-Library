# Question-Answering-Bert-SimpleTransformers-Library
Input Data Format
train= [{'context': 'Mistborn is a series of epic fantasy novels written by American author Brandon Sanderson.',
  'qas': [{'id': '00001',
    'is_impossible': False,
    'question': 'Who is the author of the Mistborn series?',
    'answers': [{'text': 'Brandon Sanderson', 'answer_start': 71}]}]},
 {'context': 'The first series, published between 2006 and 2008, consists of The Final Empire,The Well of Ascension, and The Hero of Ages.',
  'qas': [{'id': '00002',
    'is_impossible': False,
    'question': 'When was the series published?',
    'answers': [{'text': 'between 2006 and 2008', 'answer_start': 28}]},
   {'id': '00003',
    'is_impossible': False,
    'question': 'What are the three books in the series?',
    'answers': [{'text': 'The Final Empire, The Well of Ascension, and The Hero of Ages',
      'answer_start': 63}]},
   {'id': '00004',
    'is_impossible': True,
    'question': 'Who is the main character in the series?',
    'answers': []}]}]
    
    test=[{'context': 'The series primarily takes place in a region called the Final Empire on a world called Scadrial, where the sun and sky are red, vegetation is brown, and the ground is constantly being covered under black volcanic ashfalls.',
  'qas': [{'id': '00001',
    'is_impossible': False,
    'question': 'Where does the series take place?',
    'answers': [{'text': 'region called the Final Empire', 'answer_start': 38},
     {'text': 'world called Scadrial', 'answer_start': 74}]}]},
 {'context': '"Mistings" have only one of the many Allomantic powers, while "Mistborns" have all the powers.',
  'qas': [{'id': '00002',
    'is_impossible': False,
    'question': 'How many powers does a Misting possess?',
    'answers': [{'text': 'one', 'answer_start': 21}]},
   {'id': '00003',
    'is_impossible': True,
    'question': 'What are Allomantic powers?',
    'answers': []}]}]
    
    
    
