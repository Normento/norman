import SoftwareDeveloper from 'norman';
import { Languages, Frameworks } from 'norman/skills';

class Bio extends SoftwareDeveloper {
  name     = 'Norman DONOU-SEKPE';
  title    = 'Senior Web developper & Software Developer  ';
  location = 'Cotonou, BENIN';
}

class Skills extends SoftwareDeveloper {
  languages  = ['JavaScript', 'PHP', 'html', 'CSS', ...Languages];
  frameworks  = ['Laravel', 'Nodejs', 'Bootstrap', 'TailwindCSS', 'VueJS', 'React' ...Frameworks];
  CMS  = ['Wordpress', 'Shopify', 'Woocommerce', ...CMS];
  databases  = ['MySQL', 'MongoDB', 'PostgreSQL'];
}
