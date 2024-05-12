from typing import Tuple, List, Dict

class Tekky:
    pass

class Attributes(Tekky):
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "t.me/xtekky"
        channel  = "t.me/onlpx"
        email    = "github@g4f.ai"
	    
	    return telegram, channel, email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['French', 'German', 'Spanish', 'English']
        age   = 17
		
        return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['go', 'js'],
            'learning'    : ['c', 'c++', 'c#', 'asm', 'java']
        }
        specialities  = ['web/app reverse engineering', 'fullstack', 'ai']
        ide           = ['vscode']
        pc            = {
            'MacOS': {
                'macbook air m2': {
                    'processor': 'm2 | 8 cores',
                    'ram'      : '8gb',
                    'gpu'      : 'm2 | 8 cores'
                }
            },
            'Windows': {
                'custom': {
                    'processor': 'AMD ryzen 7 5800X | 8 cores',
                    'ram'      : '16gb',
                    'gpu'      : 'nvidia 3070 | 5888 CUDA cores'
                }
            }
        }

	return langs, specialities, ide, pc
