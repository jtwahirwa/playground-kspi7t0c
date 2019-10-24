<?php
    function countAllStars($galaxies) {
        $totalStars = array();
        foreach ($galaxies as $star) {
                     
            $totalStars[] = $star;
                        
        }
        $totalStars = array_sum($totalStars);
        
        return $totalStars;
    }
?>
