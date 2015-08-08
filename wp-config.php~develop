<?php
/**
 * The base configuration for WordPress
 *
 * The wp-config.php creation script uses this file during the
 * installation. You don't have to use the web site, you can
 * copy this file to "wp-config.php" and fill in the values.
 *
 * This file contains the following configurations:
 *
 * * MySQL settings
 * * Secret keys
 * * Database table prefix
 * * ABSPATH
 *
 * @link https://codex.wordpress.org/Editing_wp-config.php
 *
 * @package WordPress
 */

// ** MySQL settings - You can get this info from your web host ** //
/** The name of the database for WordPress */
define('DB_NAME', 'c9');

/** MySQL database username */
define('DB_USER', 'sudoryota');

/** MySQL database password */
define('DB_PASSWORD', '');

/** MySQL hostname */
define('DB_HOST', '0.0.0.0');

/** Database Charset to use in creating database tables. */
define('DB_CHARSET', 'utf8mb4');

/** The Database Collate type. Don't change this if in doubt. */
define('DB_COLLATE', '');

/**#@+
 * Authentication Unique Keys and Salts.
 *
 * Change these to different unique phrases!
 * You can generate these using the {@link https://api.wordpress.org/secret-key/1.1/salt/ WordPress.org secret-key service}
 * You can change these at any point in time to invalidate all existing cookies. This will force all users to have to log in again.
 *
 * @since 2.6.0
 */
define('AUTH_KEY',         'DOq?,>aNs {Cdd.*-7ar_I$gt@+MV[!)oe+_,<w.9K!uy-^[66wbC=Np^B~2^br^');
define('SECURE_AUTH_KEY',  'k}hF90^0ot.!J2s#Cd(Wk.$Aa,7Yv5@yHlF1fRk35uc4it0+_-I}mEX*=t_zE*1t');
define('LOGGED_IN_KEY',    '!Uy;7:o7g=w:ft(Jbo@1.u8tC2;Zc:{.Y{=q!EXo.~Q`2y4v9M6Xe>UIZ?c2&3Ak');
define('NONCE_KEY',        'e}:SAeu(87-:+FYk6O6-Kj&HA)3,;j%-C7)uue bMm#@,3 c.=a93::q/(X9UbeD');
define('AUTH_SALT',        'Nt%K u3#b( bd)m<=a=%J_,-[r`g3u-J)qm`8Q65hg;R&7$iuEpReH5~e8~}-D8^');
define('SECURE_AUTH_SALT', '6[@v45;O8-!Xm4MI?-A:7`5y--YF _pJ&u~2iMcO3XwU,sT2jhD>-!<f}i1PoJO5');
define('LOGGED_IN_SALT',   'daTN 6eL&O|5~~:zJA2#D!Y$zH~9aL`LBN ZdKj2:V!soHsdm)k#d0<;q/dIAx+-');
define('NONCE_SALT',       'yDwV<yX+k]-SFOb|hq,|]Aw@b&Guqft:)_pF zEaDX(c*OR;ioGwZM=tl*AOfiEl');

/**#@-*/

/**
 * WordPress Database Table prefix.
 *
 * You can have multiple installations in one database if you give each
 * a unique prefix. Only numbers, letters, and underscores please!
 */
$table_prefix  = 'wp_';

/**
 * For developers: WordPress debugging mode.
 *
 * Change this to true to enable the display of notices during development.
 * It is strongly recommended that plugin and theme developers use WP_DEBUG
 * in their development environments.
 *
 * For information on other constants that can be used for debugging,
 * visit the Codex.
 *
 * @link https://codex.wordpress.org/Debugging_in_WordPress
 */
define('WP_DEBUG', false);

/* That's all, stop editing! Happy blogging. */

/** Absolute path to the WordPress directory. */
if ( !defined('ABSPATH') )
	define('ABSPATH', dirname(__FILE__) . '/');

/** Sets up WordPress vars and included files. */
require_once(ABSPATH . 'wp-settings.php');
