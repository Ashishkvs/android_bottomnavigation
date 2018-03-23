# android_bottomnavigation
We have used Fragment and Fragment Manager 
 private boolean loadFragment(Fragment fragment){
        if(fragment !=null){
            getSupportFragmentManager()
                    .beginTransaction().replace(R.id.fragmentContainer,fragment)
                    .commit();
            return true;
        }
        return false;
    }
}
