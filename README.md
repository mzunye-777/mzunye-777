from dataclasses import dataclass
from typing import Sequence


@dataclass(frozen=True)
class Portfolio:
name: str = 'GEOFFREY MULI'
location: str = 'Nairobi Kenya'
profile: str = 'Python-Django Developer, Linux User, React Dev'
experience: str = '3+ years'
hobbies: Sequence[str] = 'Novels', 'Coffee', 'open source', 'clean code'


@dataclass(frozen=True)
class Skills:
languages: Sequence[str] = 'python', 'C','C++', '', 'JavaScript',
operation_systems: Sequence[str] = 'linux', 'Unix'


@dataclass(frozen=True)
class Social:
github: str = 'https://www.github.com/mzunye777'
codewars: str = 'https://www.codewars.com/users/geoffrey'
twitter: str = 'https://twitter.com/jfreeluv'
linkedin: str = 'https://www.linkedin.com/in/geoffreymuli'
portfolio: str = 'https://musungu.github.io'
email: str = 'mzunye777@gmail.com' 

